# Styles en ligne

Bien que le CSS soit un langage différent du HTML, il est possible d'écrire le code CSS directement dans le code HTML en utilisant des styles en ligne.

Pour styliser un élément HTML, vous pouvez ajouter l'attribut style directement à la balise d'ouverture. Après avoir ajouté l'attribut, vous pouvez le définir comme étant égal au(x) style(s) CSS que vous souhaitez appliquer à cet élément.

```html
<p style="color: red;">J'apprend à coder !</p>
```

Le code dans l'exemple ci-dessus montre comment utiliser le style en ligne. L'élément de paragraphe possède un attribut de style dans sa balise d'ouverture. Ensuite, l'attribut style est défini comme étant la couleur : rouge ; ce qui définira la couleur du texte du paragraphe en rouge dans le navigateur.

Vous vous demandez peut-être quelle est la syntaxe de l'extrait de code suivant : `color : red ;`. Pour l'instant, les détails de la syntaxe ne sont pas importants ; vous en apprendrez plus sur la syntaxe CSS dans d'autres exercices. Pour l'instant, il est important de savoir que les styles en ligne sont un moyen rapide de styliser directement un élément HTML.

Si vous souhaitez ajouter plus d'un style avec les styles en ligne, il suffit de continuer à ajouter à l'attribut style. Veillez à terminer les styles par un point-virgule ( `;`).


## A vous de jouer !

1. Récupérer le code [suivant](./versions-exercices/v0-4-1/index.html)

2. Utiliser le style en ligne pour définir la police en définissant l'attribut `font-family` du premier paragraphe sur `Arial`.
    - Remarquez vous un changement de police ?


## Réflexions

1. Qu'est ce qu'un attribut ?
    - Dans ce contexte, un attribut est un moyen d'étendre un élément HTML pour que les développeurs puissent modifier le comportement ou fournir des métadonnées sur cet élément. Les attributs sont toujours inclus dans la balise d'ouverture d'un élément HTML de cette manière :
    `<h1 style="font-size : 18px ;">`

    - L'attribut style nous permet de définir des règles CSS sur un élément, mais il existe de nombreux autres attributs. Pour en savoir plus, consultez la [documentation de Mozilla](https://developer.mozilla.org/fr/docs/Web/HTML) pour obtenir une liste complète des attributs HTML.

___

| [Précédent](../3-table-html/projet-nuit-fourrière/explications.md)       | [Suivant](./2-balise-style.md)        |
