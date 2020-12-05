# Hauteur minimum et maximum

Vous pouvez également limiter la hauteur minimale et maximale d'un élément.

- `min-height`
  - assure une hauteur minimale pour la boîte d'un élément.
  
- `max-height`
  - assure une hauteur maximale pour la boîte d'un élément.
  
```css
p {
  min-height: 150px;
  max-height: 300px;
}
```

Dans l'exemple ci-dessus, la hauteur de tous les paragraphes ne sera pas réduite en dessous de 150 pixels et la hauteur ne dépassera pas 300 pixels.

Qu'arrivera-t-il au contenu d'un élément si la propriété `max-height` est fixée trop bas pour cet élément ? Il est possible que le contenu déborde à l'extérieur de l'élément, ce qui rendrait le contenu illisible.

## A vous de jouer !

1. Reprendre votre code.

2. Encore une fois, redimensionnez votre navigateur (étirez-le). Remarquez que le texte du paragraphe peut devenir trop étendu (c'est-à-dire une petite hauteur). Limitons la hauteur pour que le texte reste lisible.
    - Dans `style.css`, fixez la hauteur minimale de tous les paragraphes à **200 pixels**.
    - Redimensionnez à nouveau votre navigateur et remarquez que le texte ne s'étale plus autant qu'avant.
    
___
| [Précédent](./6-largeur-min-max.md)       | [Suivant](./8-echelle-image-video.md)       |
