# Auto

La propriété `margin` vous permet également de centrer le contenu. Cependant, vous devez respecter quelques exigences syntaxiques. Regardez l'exemple suivant :

```css
div {
  margin: 0 auto;
}
```

Dans l'exemple ci-dessus, la ligne centrera les `divs` dans leurs éléments de contenu. Le 0 fixe les marges supérieure et inférieure à 0 pixel.
La valeur `auto` indique au navigateur d'ajuster les marges gauche et droite jusqu'à ce que l'élément soit centré dans son élément contenant.

Les éléments div dans l'exemple ci-dessus devraient être centrés sur un élément qui remplit la page, mais cela ne se produit pas. Pourquoi ?

Afin de centrer un élément, il faut définir une largeur pour cet élément.
Sinon, la largeur du `div` sera automatiquement fixée à la largeur totale de l'élément qui le contient, comme le `<body>`, par exemple. Il n'est pas possible de centrer un élément qui occupe toute la largeur de la page.

```css
div.headline {
  width: 400px;
  margin: 0 auto;
}
```

Dans l'exemple ci-dessus, la largeur de la div est fixée à *400 pixels*, ce qui est inférieur à la largeur de la plupart des écrans.
La div sera donc centrée dans un élément contenant plus de *400 pixels* de large.

## A vous de jouer !

1. Reprendre votre code.

2. Définissez la largeur des éléments de la classe `.pull-quote` à 350 pixels.

3. Mettez les marges verticales de l'élément `#main` à `0`, et les marges horizontales à `auto.

___

| [Précédent](./5-marge.md)       | [Suivant](./7-effondrement-marge.md)     |
