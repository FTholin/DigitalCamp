# Align-content

Maintenant que les éléments peuvent passer à la ligne suivante, nous pourrions avoir plusieurs rangées d'éléments souples dans le même conteneur. Dans un exercice précédent, nous avons utilisé la propriété `align-items` pour espacer les éléments souples du haut vers le bas d'un conteneur souple. `align-items` permet d'aligner les éléments dans une seule rangée. Si un conteneur souple a plusieurs rangées de contenu, nous pouvons utiliser `align-content` pour espacer les rangées du haut vers le bas.

`align-content` accepte six valeurs :

- `flex-start`
  - toutes les rangées d'éléments seront placées en haut du conteneur parent sans espace supplémentaire entre eux.
- `flex-end` 
  - toutes les rangées d'éléments seront positionnées en bas du conteneur parent sans espace supplémentaire entre eux.
`center` 
  - toutes les rangées d'éléments seront positionnées au centre de l'élément parent sans espace supplémentaire entre eux.
- `space-between` 
  - toutes les rangées d'éléments seront espacées uniformément du haut au bas du conteneur, sans espace au-dessus du premier ou en dessous du dernier.
- `space-around` 
  - toutes les rangées d'éléments seront espacées uniformément du haut vers le bas du conteneur avec le même espace en haut et en bas et entre chaque élément.
- `stretch` 
  - si une hauteur minimale ou aucune hauteur n'est spécifiée, les rangées d'éléments s'étireront pour remplir le conteneur parent de haut en bas (valeur par défaut).
  
```html
<div class="container">
  <div class=”child”>
    <h1>1</h1>
  </div>
  <div class="child">
    <h1>2</h1>
  </div>
  <div class="child">
    <h1>3</h1>
  </div>
  <div class="child">
    <h1>4</h1>
  </div>
</div>
```
```css
.container {
  display: flex;
  width: 400px;
  height: 400px;
  flex-wrap: wrap;
  align-content: space-around;
}
 
.child {
  width: 150px;
  height: 150px;
}
```

Dans l'exemple ci-dessus, il y a quatre articles souples à l'intérieur d'un conteneur souple. Les éléments flexibles sont définis pour avoir une largeur de 150 pixels chacun, mais le conteneur parent n'a que 400 pixels de largeur. Cela signifie qu'il n'est pas possible d'afficher plus de deux éléments en ligne.  
Les deux autres éléments s'enrouleront sur la ligne suivante et il y aura deux rangées de divs à l'intérieur du conteneur flex.  
La propriété `align-content` est définie à la valeur d'espacement, ce qui signifie que les deux rangées de divs seront espacées de manière égale du haut vers le bas du conteneur parent avec un espacement égal avant la première rangée et après la seconde, avec un doublement de l'espace entre les rangées.

Note : La propriété `align-content` se déclare sur les conteneurs souples.

## A vous de jouer !

1. Reprendre le code [suivant](./versions-exercices/v0-13-11/).

2. Définissez la propriété `align-content` de `#flexstart` à `flex-start`.

3. Définissez la propriété `align-content` de `#flexend` à `flex-end`.

4. Définissez la propriété `align-content` de `#center` à `center`.

5. Définissez la propriété `align-content` de `#between` à `space-between`.

6. Définissez la propriété `align-content` de `#around` à `space-around`.

7. Modifiez la déclaration de hauteur dans la règle CSS `.left, .center, .right` pour indiquer la hauteur minimale à la place. Que se passe-t-il avec les éléments souples dans le conteneur `#stretch` ?


___
| [Précédent](./10-flex-wrap.md)       | [Suivant](./12-flex-direction.md)    |
