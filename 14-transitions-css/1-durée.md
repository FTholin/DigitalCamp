# Durée

Pour créer une transition simple dans le CSS, nous devons préciser deux des quatre aspects :

  - La propriété que nous voulons faire passer.
  - La durée de la transition.
  
```css
a {
  transition-property: color;
  transition-duration: 1s;
}
```

Dans l'exemple ci-dessus, `transition-property` déclare la propriété CSS que nous allons animer, la couleur du texte. La seconde propriété, `transition-duration`, déclare la durée de la transition est d'une seconde.

De nombreux changements d'état des propriétés peuvent être transitoires. 
Le type de transition dépend de la propriété que vous choisissez.
Pour une liste complète de toutes les propriétés animées, consultez cette [ressource](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_animated_properties).

Par exemple, les différentes propriétés :

Les valeurs de couleur, comme  la couleur `color` et la couleur de fond `background-color`, se fondent dans une nouvelle couleur.
Les valeurs de longueur, comme `font-size`, `width`, et `height`, augmenteront ou diminueront.
La durée est spécifiée en secondes ou en millisecondes, par exemple `3s`, `0,75s`, `500ms`. La valeur par défaut est `0s`, ou instantanée, comme s'il n'y avait pas de transition.

Lorsque vous choisissez une durée, pensez à la durée des actions dans la vie réelle. Par exemple, un clignement d'œil humain dure environ 400 ms. Les gens peuvent s'attendre à ce que l'animation d'un clic sur un bouton soit aussi soudaine qu'un clignement.

## A vous de jouer !

1. Reprendre le code [suivant](./exercices-versions/v0-14-1/).

2. Dans la règle `a` ajoutez les propriétés suivantes:
```css
{
  transition-property: background-color;
  transition-duration: 2s;
}
```

3. Tout compte fais régler la durée de la transition à 750 milliseconds.


___
| [Précédent](../13-flexbox/liste-taches/explications.md)       |  [Suivant](./2-delai.md)  |
