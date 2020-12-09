# flex-wrap

Parfois, nous ne voulons pas que notre contenu rétrécisse pour s'adapter à son contenant. Au contraire, nous désirons que les articles flexibles passent à la ligne suivante si nécessaire. Cela peut être déclaré avec la propriété `flex-wrap`. 

La propriété `flex-wrap` peut accepter trois valeurs :
1. `wrap`
  - les éléments enfants d'un conteneur souple qui ne tiennent pas dans une rangée se déplacent vers la ligne suivante
2. `wrap-reverse`
  - même fonctionnalité que `wrap`, mais l'ordre des rangées dans un conteneur souple est inversé (par exemple, dans une boîte souple à 2 rangées, la première rangée d'un conteneur `wrap` deviendra la deuxième dans le `wrap-reverse` et la deuxième rangée du conteneur `wrap` deviendra la première dans le `wrap-reverse`)
3. `nowrap`
  - empêche l'emballage des articles ; c'est la valeur par défaut et elle est seulement nécessaire pour remplacer une valeur d'emballage fixée par une autre règle CSS.

```html
<div class="container">
  <div class="item">
    <h1>Nous allons emballer !</h1>
  </div>
  <div class="item">
    <h1>Nous allons emballer !</h1>
  </div>
  <div class="item">
    <h1>Nous allons emballer !</h1>
  </div>
</div>
```

```css
.container {
  display: inline-flex;
  flex-wrap: wrap;
  width: 250px;
}
 
.item {
  width: 100px;
  height: 100px;
}
```

Dans l'exemple ci-dessus, trois articles souples sont contenus par un conteneur souple parent. Le conteneur souple n'a que 250 pixels de large, de sorte que les trois articles souples de 100 pixels de large ne peuvent pas être alignés. Le paramètre `flex-wrap : wrap ;` fait apparaître le troisième élément débordant sur une nouvelle ligne, en dessous des deux autres éléments.

Note : La propriété `flex-wrap` est déclarée sur les conteneurs souples.

## A vous de jouer !

1. Reprendre le code [suivant](./versions-exercices/v0-13-10/)

2. Ajoutez une propriété `flex-wrap` avec la valeur `wrap` à la div  `#wrap`. Réduire et étirer le navigateur pour tester.

3. Ajoutez une propriété `flex-wrap` avec la valeur `nowrap` à la div `#nowrap`. Réduire et étirer le navigateur pour tester.

4. Ajoutez une propriété `flex-wrap` avec la valeur `wrap-reverse` à la div `#reverse`. Réduire et étirer le navigateur pour tester.

5. Ajoutez une propriété `justify-content` avec la valeur `space-around` à la classe `.container`. Réduire et étirer le navigateur pour tester.


___
| [Précédent](./9-flex.md)       | [Suivant](./11-align-content.md)    |
