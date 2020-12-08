# Spécificité

La spécificité est l'ordre dans lequel le navigateur décide des styles CSS qui seront affichés. Une des meilleures pratiques en matière de CSS consiste à styliser les éléments en utilisant le degré de spécificité le plus bas, de sorte que si un élément a besoin d'un nouveau style, il est facile de l'ignorer.

Les ID sont le sélecteur le plus spécifique en CSS, suivis des classes et enfin des balises. Prenons par exemple les exemples suivants de HTML et CSS :  
`Html`
```html
<h1 class="headline">Annonces fracassantes</h1>
```
`CSS`
```css
h1 {
  color: red;
}

.headline {
  color: green;
}
```

Dans l'exemple de code ci-dessus, la couleur de l'intitulé sera fixé à `green`, car le sélecteur de classe est plus spécifique que le sélecteur de balise.
Si un attribut ID (et un sélecteur) était ajouté au code ci-dessus, les styles dans le corps du sélecteur ID auraient la priorité sur tous les autres styles pour la rubrique.
La seule façon de remplacer un ID est d'ajouter un autre ID avec un style supplémentaire.


Avec le temps, à mesure que les fichiers se développent avec le code, de nombreux éléments peuvent avoir des ID, ce qui peut rendre le CSS difficile à modifier, car il faut créer un nouveau style plus spécifique pour changer le style d'un élément.

Pour faciliter la modification des styles, il est préférable d'utiliser un sélecteur de balises, si possible.
Sinon, ajoutez un sélecteur de classe. Si cela n'est pas assez spécifique, envisagez alors d'utiliser un sélecteur d'ID.

## A vous de jouer !
1. Reprendre votre code.

2. Dans le fichier HTML, l'élément de la `ligne 11` a une balise `h1`, deux classes et un identifiant.
Comme l'ID est plus spécifique que les deux, ses styles seront appliqués à l'élément.
Réécrivons l'ID de cet élément pour qu'il soit moins spécifique en créant des classes.
    - Dans le fichier HTML, supprimez l'attribut `id` de l'élément `h1` sur la `ligne 11`.

3. Supprimez maintenant l'id `article-title` et l'id `article-id` avec son contenu dans le CSS.

4. Dans le CSS, ajouter un sélecteur de classe nommé `.cursive`. A l'intérieur de son corps, écrivez :
    `font-family: cursive;`
    
5. Ajoutez un autre sélecteur de classe nommé `.capitalize`. Dans ses accolades, écrivez :
    `text-transform: capitalize;`

6. Dans le fichier HTML, remplacez la classe `uppercase` par la classe `cursive` et `capitalize` dans le `h1` à la `ligne 11`.

___
| [Précédent](./9-classes-ids.md)       | [Suivant](./11-enchainement-selecteurs.md)        |
