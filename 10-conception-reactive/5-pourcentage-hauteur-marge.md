# Pourcentage Rembourrage & Marge

Les pourcentages peuvent également être utilisés pour fixer le rembourrage et la marge des éléments.

Lorsque la hauteur `height` et la largeur `width` sont définies à l'aide de pourcentages, vous avez appris que les dimensions des éléments enfants sont calculées sur la base des **dimensions de l'élément parent**.

En revanche, lorsque les pourcentages sont utilisés pour définir le `padding` et la `margin`, ils sont **calculés uniquement en fonction de la largeur de l'élément parent**.

Par exemple, lorsqu'une propriété comme margin-left est définie à l'aide d'un pourcentage (disons 50%), l'élément sera déplacé à mi-chemin vers la droite dans le conteneur parent (par opposition à l'élément enfant qui reçoit une marge égale à la moitié de la marge de son parent).

Le rembourrage vertical et la marge sont également calculés en fonction de la largeur du parent.

Considérons le scénario suivant :

1. Une `div` conteneur est défini, mais sa hauteur n'est pas fixée (c'est-à-dire qu'il est plat).
2. Un élément enfant est alors ajouté au conteneur. L'élément enfant a une hauteur déterminée. La hauteur de son conteneur parent s'étend donc jusqu'à cette hauteur.
3. L'élément enfant nécessite un changement, et sa hauteur est modifiée. Ainsi, la hauteur du conteneur parent s'étend également à la nouvelle hauteur. Ce cycle se produit sans fin chaque fois que la hauteur de l'élément enfant est modifiée

Dans le scénario ci-dessus, une taille non fixée (celle du parent) entraîne un changement constant de la taille en raison des modifications de l'élément enfant. C'est pourquoi le rembourrage vertical et la marge sont basés sur la largeur du parent, et non sur la hauteur.

Note : Lorsque la taille relative est utilisée, il convient d'utiliser les lettres ems et rems pour dimensionner le texte et les dimensions de la page en fonction de la taille du texte (c'est-à-dire le rembourrage autour du texte). Cela permet de créer une mise en page cohérente en fonction de la taille du texte. Dans le cas contraire, il convient d'utiliser des pourcentages.

## A vous de jouer !

1. Reprendre votre code.

2. Dimensionnons la hauteur de la bannière par rapport à la taille de police de l'élément racine.
    - Dans `style.css`, pour le sélecteur `#banner`, ajoutez une propriété de hauteur et attribuez la à `46rem`.
> **Remarque** : La taille de police de l'élément racine est de 16 pixels, ce qui signifie que `46rem` donnera une hauteur de *736 pixels*.

3. Définissez la marge supérieure de `#banner h1` à `12.5%`.

4. Définissez la marge inférieure de `#blog .post` à `7.5%`.

5. Définissez la marge inférieure de `.images` à `20%`.

___
| [Précédent](./4-pourcentage-hauteur-largeur.md)       | [Suivant](./6-largeur-min-max.md)       |
