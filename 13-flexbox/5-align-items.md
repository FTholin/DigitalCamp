# align-items

Dans l'exercice précédent, vous avez appris à justifier le contenu d'un conteneur flex de gauche à droite sur toute la page. Il est également possible d'aligner les éléments flex verticalement à l'intérieur du conteneur. La propriété `align-items` permet d'espacer les éléments flexibles verticalement.

```css
.container {
  align-items: baseline;
}
```

Dans l'exemple ci-dessus, la propriété "align-items" est fixée à `baseline`. Cela signifie que la ligne de base du contenu de chaque élément sera alignée.

Il y a cinq valeurs que nous pouvons utiliser pour la propriété `align-items` :

- `flex-start`
  - tous les éléments seront placés en haut du conteneur parent.
  
- `flex-`
  - tous les éléments seront positionnés au bas du conteneur parent.
  
- `center`
  - le centre de tous les éléments sera positionné à mi-chemin entre le haut et le bas du conteneur parent.

- `baseline`
  - le bas du contenu de tous les éléments sera aligné avec le bas du conteneur parent.
  
- `stretch`
  - si possible, les éléments s'étireront du haut vers le bas du conteneur (c'est la valeur par défaut ; les éléments ayant une hauteur spécifiée ne s'étireront pas ; les éléments ayant une hauteur minimale ou aucune hauteur spécifiée s'étireront).
  
Ces cinq valeurs indiquent aux éléments comment se comporter le long de l'axe transversal du conteneur parent. Dans ces exemples, l'axe transversal s'étend de haut en bas du conteneur. Nous en apprendrons plus à ce sujet dans un prochain exercice.

Vous n'êtes peut-être pas familier avec les propriétés `min-height` et `max-height`, mais vous connaissez bien `height` et `width`.
Ces propriétés garantissent qu'un élément a au moins une certaine taille ou tout au plus une certaine dimension.

## A vous de jouer !

1. Reprendre le code [suivant](./versions-exercices/v0-13-5/).

2. Attribuez à la div ayant l'id `#flexstart` la propriété `align-items` avec pour valeur `flex-start`.
3. Attribuez à la div ayant l'id `#flexend` la propriété `align-items` avec pour valeur `flex-end`.
4. Attribuez à la div ayant l'id `#center` la propriété `align-items` avec pour valeur `center`.
5. Attribuez à la div ayant l'id `#baseline` la propriété `align-items` avec pour valeur `baseline`.
6. Dans le sélecteur `.left, .right, .center` changer `height` pour `min-height`. 

___
| [Précédent](./4-justify-content.md)       | [Suivant](./6-flex-grow.md)    |
