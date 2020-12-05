# Attribut Id

Si un élément HTML doit avoir un style unique (quelles que soient les classes appliquées à l'élément), nous pouvons ajouter un ID à l'élément. Pour ajouter un ID à un élément, l'élément a besoin d'un attribut `id` :

```html
<h1 id="large-title"> ... </h1>
```

Ensuite, le CSS peut sélectionner les éléments HTML par leur attribut `id`. Pour sélectionner un élément `id`, le CSS ajoute un hashtag (`#`) au nom de l'`id`. Par exemple, si nous voulions sélectionner l'élément HTML dans l'exemple ci-dessus, il ressemblerait à ceci :

```css
#large-title {

}
```

Le nom de l'identifiant est `large-title`, donc le sélecteur CSS pour lui est `#large-title`.

## A vous de jouer !

1. Reprendre votre code.

2. Dans le fichier CSS, ajouter un sélecteur CSS pour un élément avec un identifiant (`id`) de `article-title`. A l'intérieur de ses accolades, écrivez :
    ```css
    font-family: cursive;
    text-transform: capitalize;
    ```

    Ces deux attributs CSS rendront la police cursive et mettront en majuscules la première lettre de chaque mot, tout en mettant en minuscules le reste.

3. Dans le fichier HTML, à la ligne 11, ajoutez un attribut `id` à l'élément `h1`, et incluez `article-title` comme son `id`. Vous verrez le titre se transformer en une police cursive qui n'est pas entièrement en majuscules.

___

| [Précédent](./7-classes-multiples.md)       | [Suivant](./9-classes-ids.md)        |
