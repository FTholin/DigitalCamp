# Flexbox emboîtées

Jusqu'à présent, nous avons eu plusieurs conteneurs flexibles sur la même page pour explorer le positionnement des articles flexibles. Il est également possible de positionner les conteneurs flex les uns dans les autres.

```html
<div class="container">
  <div class="left">
    <img class="small" src="#"/>
    <img class="small" src="#"/>
    <img class="small" src="#" />
  </div>
  <div class="right">
    <img class="large" src="#" />
  </div>
</div>
```

```css
.container {
  display: flex;
  justify-content: center;
  align-items: center;
}
 
.left {
  display: inline-flex;
  flex: 2 1 200px;
  flex-direction: column;
}
 
.right {
  display: inline-flex;
  flex: 1 2 400px;
  align-items: center;
}
 
.small {
  height: 200px;
  width: auto;
}
 
.large {
  height: 600px;
  width: auto;
}
```

Dans l'exemple ci-dessus, une div avec trois images plus petites s'affichera de haut en bas à gauche de la page (`.left`). Il existe également une div avec une grande image qui s'affiche sur le côté droit de la page (`.droite`). La division de gauche a une base plus petite mais s'étire pour remplir plus d'espace supplémentaire ; la division de droite a une base plus grande mais s'étire pour remplir moins d'espace supplémentaire. Les deux divisions sont des articles et des conteneurs souples. Les articles ont des propriétés qui dictent comment ils seront positionnés dans le conteneur parent et comment leurs enfants seront positionnés dans les articles souples.

Nous utiliserons le même formatage que ci-dessus pour mettre en page la page simple à droite.

## A vous de jouer !

1. Reprendre le code  [suivant](./versions-exercices/v0-13-14/).

2. Définissez la propriété `display` de `.main` sur `flex`.

3. Définissez la propriété `align-items` de `.main` sur `center`.

___
| [Précédent](./13-flex-flow.md)       | [Suivant (Projet)](./liste-taches/explications.md)    |
