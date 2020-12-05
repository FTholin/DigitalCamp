# Inline-flex

Dans l'exercice précédent, vous avez peut-être remarqué que lorsque nous avons donné à un div - un élément de niveau bloc - la valeur flex à `display`, il est resté un élément de niveau bloc.
Que faire si nous voulons que plusieurs conteneurs flex s'affichent en ligne les uns avec les autres ?

Si nous ne voulions pas que les éléments div soient des éléments de niveau bloc, nous utiliserions `display : inline`. 
Flexbox, cependant, fournit la valeur `inline-flex` pour l'attribut display, ce qui nous permet de créer des conteneurs flex qui sont également des éléments inline.

```html
<div class="container">
  <p>Je suis dans un conteneur souple</p>
  <p>Les enfants d'un conteneur souple sont des éléments souples !</p>
</div>
<div class="container">
  <p>Je suis également un élément souple</p>
  <p>Moi aussi</p>
</div>

```

```css
.container {
  width: 200px;
  height: 200px;
  display: inline-flex;
}
```

Dans l'exemple ci-dessus, il y a deux divs conteneurs. Sans largeur, chaque div s'étendrait sur toute la largeur de la page. Les paragraphes à l'intérieur de chaque div s'afficheraient également les uns sur les autres car les paragraphes sont des éléments de niveau bloc.

Lorsque nous changeons la valeur de la propriété d'affichage en inline-flex, les divs s'affichent en ligne les uns avec les autres si la page est suffisamment large. Au fil de cette leçon, nous aborderons plus en détail la manière dont les éléments flex sont affichés.

Notez que dans l'exemple ci-dessus, la taille du conteneur flex est définie. Actuellement, la taille du conteneur parent a priorité sur la taille de ses éléments enfants. Si l'élément parent est trop petit, les éléments flexibles se réduiront pour s'adapter à la taille du conteneur parent.


```html
<div class="container">
  <div class="child">
    <h1>1</h1>
  </div>
  <div class="child">
    <h1>2</h1>
  </div>
</div>
```

```css
.container {
  width: 200px;
}

.child {
  display: inline-flex;
  width: 150px;
  height: auto;
}
```

Dans l'exemple ci-dessus, les divs `.child` prendront plus de largeur (300 pixels) que la div `container` ne le permet (200 pixels). Les divs `.child`  rétréciront pour s'adapter à la taille du conteneur.

## A vous de jouer !
1. Reprendre le code [suivant](./versions-exercices/v0-13-3/)

2. Réglez la propriété `display` du div `.container` sur `inline-flex`.

___
| [Précédent](./2-flex.md)       | [Suivant](./4-justify-content.md)|
