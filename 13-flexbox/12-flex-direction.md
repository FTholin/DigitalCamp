# flex-direction

Jusqu'à présent, nous n'avons couvert que les articles flexibles qui s'étirent et se rétractent horizontalement et s'enroulent verticalement. Comme indiqué précédemment, les conteneurs souples ont deux axes : un axe principal et un axe transversal. Par défaut, l'axe principal est horizontal et l'axe transversal est vertical.

L'axe principal est utilisé pour positionner les articles flexibles ayant les propriétés suivantes :

1. `justify-content`
2. `flex-wrap`
3. `flex-grow`
4. `flex-shrink`

L'axe transversal est utilisé pour positionner les articles souples ayant les propriétés suivantes :

- `align-items`
- `align-content`

L'axe principal et l'axe transversal sont interchangeables. Nous pouvons les changer en utilisant la propriété `flex-direction`. Si nous ajoutons la propriété `flex-direction` et lui donnons une valeur de colonne, les éléments souples seront ordonnés verticalement, et non horizontalement.

```html
<div class="container">
  <div class="item">
    <h1>1</h1>
  </div>
  <div class="item">
    <h1>2</h1>
  </div>
  <div class="item">
    <h1>3</h1>
  </div>
  <div class="item">
    <h1>4</h1>
  </div>
  <div class="item">
    <h1>5</h1>
  </div>
</div>
```
```css
.container {
  display: flex;
  flex-direction: column;
  width: 1000px;
}
.item {
  height: 100px;
  width: 100px;
}
```

Dans l'exemple ci-dessus, les cinq divs seront positionnées dans une colonne verticale. Toutes ces divs pourraient tenir sur une seule ligne horizontale. Cependant, la valeur de la colonne indique au navigateur d'empiler les divs les unes sur les autres.  
Comme expliqué ci-dessus, des propriétés comme ` justify-content` ne se comporteront pas comme dans les exemples précédents.

La propriété "flex-direction" peut accepter quatre valeurs :

- `row` 
  - les éléments seront positionnés de gauche à droite sur l'élément parent en partant du coin supérieur gauche (par défaut).
- `row-reverse` 
  - les éléments seront positionnés de droite à gauche sur l'élément parent en partant du coin supérieur droit.
- `column` 
  - les éléments seront placés de haut en bas de l'élément parent en partant du coin supérieur gauche.
- `column-reverse` 
  - les éléments seront positionnés de bas en haut de l'élément parent à partir du coin inférieur gauche.
 


## A vous de jouer !

1. Reprendre le code [suivant](./versions-exercices/v0-13-12/)
2. Donnez à `#row` la propriété `flex-direction: row;`.
3. Donnez à `#row-reverse` la propriété `flex-direction: row-reverse;`.
4. Donnez à `#column` la propriété 'flex-direction: column;'.
5. Donnez à `#column-reverse` la propriété 'flex-direction: column-reverse;'.
6. Remplacez la propriété `height` de `.container` par `max-height`.
   -  N'oubliez pas d'étirer et de rétrécir le navigateur après chaque point de contrôle pour que vous puissiez en voir les effets.
7. Donnez à `.container` la propriété `align-items: center;`.
8. Donnez à `.container` la propriété `justify-content: space-around;`.
9. Définissez la propriété `flex-grow` de classe `.box` à 1. Dans quelle direction les éléments croissent-ils ?


___
| [Précédent](./11-align-content.md)       | [Suivant](./13-flex-flow.md)    |
