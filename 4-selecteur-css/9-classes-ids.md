# Classes and IDs

Le CSS peut sélectionner les éléments HTML par leur balise, leur classe et leur ID. Les classes et les ID CSS ont des objectifs différents, ce qui peut affecter celui que vous utilisez pour styliser les éléments HTML.

Les classes CSS sont destinées à être réutilisées sur de nombreux éléments. En écrivant des classes CSS, vous pouvez styliser les éléments de différentes manières en mélangeant les classes sur les éléments HTML.

Par exemple, imaginez une page avec deux titres. Un titre doit être en gras et en bleu, et l'autre en gras et en vert. Au lieu d'écrire des règles CSS séparées pour chaque titre qui répètent le code de l'autre, il vaut mieux écrire une règle CSS `.bold`, une règle CSS `.green` et une règle CSS `.blue`. Vous pouvez alors donner à un titre les classes vertes en gras et à l'autre les classes bleues en gras.

Alors que les classes sont censées être utilisées à de nombreuses reprises, un ID ne sert à styliser qu'un seul élément. Comme nous l'apprendrons dans le prochain exercice, les ID ont priorité sur les styles des balises et des classes. Comme les ID ont priorité sur les styles des classes et des balises, ils doivent être utilisés avec parcimonie et uniquement sur les éléments qui doivent toujours avoir la même apparence.

## A vous de jouer !

Sur la ligne 13 du HTML, il y a un élément qui affiche l'heure à laquelle l'article a été publié sur la page.

1. Reprenez votre code.

2. Ajoutez un attribut de classe, avec une classe  `publish-time`.

3. Ajouter un sélecteur `publish-time`dans le fichier CSS, rendez son texte de couleur grise en l'écrivant dans le corps de la règle CSS :
    ```css
    color: gray;
    ```

___

| [Précédent](./8-attribut-id.md)       | [Suivant](./10-specificite.md)        |
