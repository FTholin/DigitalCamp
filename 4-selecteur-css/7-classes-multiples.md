# Classes multiples

Nous pouvons utiliser le CSS pour sélectionner l'attribut de classe d'un élément HTML par son nom.

Jusqu'à présent, nous avons sélectionné les éléments en utilisant un seul nom de classe par élément.
Si chaque élément HTML avait une seule classe, toutes les informations de style pour chaque élément nécessiteraient une nouvelle classe.

Heureusement, il est possible d'ajouter plus d'un nom de classe à l'attribut de classe d'un élément HTML.

Par exemple, un élément d'en-tête doit être vert et en gras. Vous pourriez écrire deux règles CSS de cette manière :

```css
.green {
  color: green;
}

.bold {
  font-weight: bold;
}
```

Ensuite, vous pourriez inclure ces deux classes sur un élément HTML comme ceci :

```html
<h1 class="green bold"> ... </h1>
```

Nous pouvons ajouter plusieurs classes à l'attribut de classe d'un élément HTML en les séparant par un espace. Cela nous permet de mélanger et de faire correspondre les classes CSS pour créer de nombreux styles uniques sans avoir à écrire une classe personnalisée pour chaque combinaison de style nécessaire.


## A vous de jouer !

1. Dans le fichier CSS, ajoutez un sélecteur de classe qui fera ressortir davantage le titre de la page en mettant toutes ses lettres en majuscules. Ecrivez une classe nommée `.uppercase`. Ensuite, écrivez ceci à l'intérieur de ses accolades :
    ```css
    text-transform: uppercase;
    ```

2. Vous pouvez maintenant ajouter la classe à l'élément `title`. Dans le fichier HTMl, sur la ligne 11, il y a un élément `<h1>` qui a une classe `title`. Ajoutez la classe `uppercase` à cet élément.

___

| [Précédent](./6-attribut-classe.md)       | [Suivant](./8-attribut-id.md)        |
