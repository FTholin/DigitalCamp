# Pourcentages : Hauteur et largeur

Pour dimensionner les éléments HTML non textuels par rapport à leurs éléments parents sur la page, vous pouvez utiliser des pourcentages.

Les pourcentages sont souvent utilisés pour dimensionner les valeurs des modèles de boîtes, comme la largeur et la hauteur, le rembourrage, la bordure et les marges.

Ils peuvent également être utilisés pour définir les propriétés de positionnement (haut, bas, gauche, droite).

Pour commencer, dimensionnons la hauteur et la largeur d'un élément en utilisant des pourcentages.

```css
.main {
  height: 300px;
  width: 500px;
}

.main .subsection {
  height: 50%;
  width: 50%;
}
```

Dans l'exemple ci-dessus, `.main` et `.subsection` représentent chacune des divs.
La division `.subsection` est imbriquée dans la division `.main`.
Notez que les dimensions de la div parent (`.main`) ont été fixées à une hauteur de **300 pixels** et une largeur de **500 pixel**s.

Lorsque des pourcentages sont utilisés, les éléments sont dimensionnés par rapport aux dimensions de leur élément parent (également appelé conteneur). 
Par conséquent, les dimensions du div `.subsection` seront de **150 pixels** de hauteur et de **250 pixels** de largeur.
Attention, les dimensions d'un élément enfant peuvent être définies de manière erronée si les dimensions de son élément parent ne sont pas définies au préalable.

**Remarque** : comme le modèle de boîte comprend un **rembourrage**, des **bordures** et des **marges**, le fait de fixer la largeur d'un élément à 100 % peut faire en sorte que le contenu déborde de son conteneur d'origine.
Bien que cela soit tentant, la valeur **100 %** ne doit être utilisée que lorsque le contenu ne comporte pas de **rembourrage**, de **bordure** ou de **marge**.

## A vous de jouer !

1. Reprendre votre code.

2. Actuellement, le blog occupe toute la largeur du `body`.
    - Modifions cela pour qu'il ne s'étende pas pour remplir toute la largeur.
    - Dans `style.css`, définissez la largeur dans `#blog` à `86%`.
    - Cela permettra de régler le conteneur du blog à 86 % de la largeur totale du corps.
    
3. Remarquez que le texte du blog devient illisible en plus petite largeur.
    - Pour y remédier, définissez la largeur dans `#blog .post` à 52 %.
    - Ainsi, le texte ne remplira que 52 % de la largeur de son conteneur (`#blog`).
    - Redimensionnez le navigateur maintenant et remarquez comment le texte reste lisible.
    
4. Définissez maintenant la largeur de `.post .image-container` à `100%`.
    - Cela permettra de s'assurer que le conteneur de l'image est toujours de la même largeur que l'article du blog (`.post`).

5. Faites défiler l'écran jusqu'au bas de la page web. Remarquez qu'il y a deux images. Nous aimerions afficher ces images l'une à côté de l'autre sur la page, avec une largeur égale.
    - Définissez la largeur dans `.images .image-container` à `50%`. 
    - Cela donnera à chaque image en `.images` une largeur égale.
    - Ne vous inquiétez pas si les images ont encore l'air déformées pour le moment.
    
 
___
| [Précédent](./3-rem.md)       | [Suivant](./5-pourcentage-hauteur-marge.md)       |
