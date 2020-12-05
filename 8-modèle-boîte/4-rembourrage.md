# Rembourage ou padding

L'espace entre le contenu d'une boîte et les bords d'une boîte est appelé rembourrage ou `padding`.
Le `padding` est comme l'espace entre une photo et le cadre qui l'entoure.
En CSS, vous pouvez modifier cet espace grâce à la propriété `padding`.

```css
p.content-header {
  border: 3px solid coral;
  padding: 10px;
}
```

Dans cet exemple, le code place 10 pixels d'espace entre le contenu du paragraphe (le texte) et les bordures, sur les quatre côtés.

La propriété `padding` est souvent utilisée pour étendre la couleur de fond et rendre le contenu moins encombrant.

Si vous souhaitez être plus précis quant à la quantité de remplissage de chaque côté du contenu d'une boîte, vous pouvez utiliser les propriétés suivantes :

- `padding-top`
- `padding-right`
- `padding-bottom`
- `padding-left`

Chaque propriété n'affecte le `padding` que d'un seul côté du contenu de la boîte, ce qui vous donne plus de souplesse dans la personnalisation.

```css
p.content-header {
  border: 3px solid fuschia;
  padding-bottom: 10px;
}
```


Dans l'exemple ci-dessus, seul le côté inférieur du contenu du paragraphe aura un `padding` de 10 pixels.

Une autre implémentation de la propriété de `padding` vous permet de spécifier exactement la quantité de `padding` qu'il doit y avoir de chaque côté du contenu dans une seule déclaration.

```css
p.content-header {
  border: 3px solid grey;
  padding: 6px 11px 4px 9px;
}
```

Dans l'exemple ci-dessus, les quatre valeurs `6px 11px 4px 9px`. Dans l'ordre, elle indique la quantité de remplissage sur les côtés supérieur (6 pixels), droit (11 pixels), inférieur (4 pixels) et gauche (9 pixels) du contenu.

Lorsque nous utilisons cette implémentation de la propriété de `padding`, nous devons spécifier une valeur de `padding` pour les quatre côtés de l'élément.

Cependant, si les valeurs de padding supérieure et inférieure sont égales, et si les valeurs de padding gauche et droite sont également égales, vous pouvez utiliser le raccourci suivant :

```css
p.content-header {
  padding: 5px 10px;
}
```

La première valeur, `5px`, définit la valeur de remplissage pour les côtés supérieur et inférieur du contenu. La deuxième valeur, `10px`, définit la valeur de remplissage pour les côtés gauche et droit du contenu.



## A vous de jouer !

1. Reprendre votre code.

2. En une ligne, Stylisez les éléments `.navigation li` pour qu'ils aient `20 pixels` de `padding`. Cliquez sur Exécuter et observez leur changement.

3. Observez les cases rouges en bas de la page web. Stylisez les éléments  `.share a` pour avoir `14 pixels` de `padding` dans `style.css` et lancez votre code. Observez comment les cases rouges au bas de la page ont changé.

4. Définissez le `padding` supérieur et inférieur des éléments `<h2>` à `20 pixels` et réglez le `padding` gauche et droit des éléments `<h2>` à `30 pixels`.

___

| [Précédent](./3-rayon-bordure.md)       |  [Suivant](./5-marge.md)       |
