# Bonnes pratiques du développeur
## Espace

À mesure que le code d'un fichier HTML se développe, il devient de plus en plus difficile de suivre la façon dont les éléments sont liés. Les programmeurs utilisent deux outils pour visualiser la relation entre les éléments : l'espace et l'indentation.

Ces deux outils tirent parti du fait que la position des éléments dans un navigateur est indépendante de la quantité d'espacement ou d'indentation dans le fichier `index.html`.

Par exemple, si vous souhaitez augmenter l'espace entre deux paragraphes de votre page web, vous ne pourrez pas le faire en ajoutant de l'espace entre les éléments du paragraphe dans le fichier index.html. Le navigateur ignore les espaces dans les fichiers HTML lorsqu'il rend une page web, il peut donc être utilisé comme un outil pour rendre le code plus facile à lire et à suivre.

Qu'est-ce qui rend l'exemple ci-dessous difficile à lire ?

```html
<body><p>Paragraphe 1</p><p>Paragraphe 2</p></body>
```

Vous devez lire la ligne entière pour savoir quels éléments sont présents. Comparez l'exemple ci-dessus avec celui-ci :

```html
<body>
    <p>Paragraphe 1</p>
    <p>Paragraphe 2</p>
</body>
```

Cet exemple est plus facile à lire, car chaque élément se trouve sur sa propre ligne. Alors que dans le premier exemple, il fallait lire toute la ligne de code pour identifier les éléments, cet exemple permet d'identifier facilement la balise "`body`" et deux paragraphes.

Un navigateur rend les deux exemples de la même manière :

```
Paragraphe 1
Paragraphe 2
```

## Indentation
Le deuxième outil utilisé par les développeurs web pour rendre la structure du code plus facile à lire est l'indentation. Les espaces sont insérés à l'aide des barres d'espacement et de tabulation de votre clavier.

Le World Wide Web Consortium, ou W3C, est chargé de maintenir les normes de style du HTML. Au moment de la rédaction du présent document, le [W3C](https://www.w3.org/) recommande 2 espaces d'indentation lors de l'écriture de code HTML. Bien que votre code fonctionne sans exactement deux espaces, cette norme est suivie par la majorité des développeurs web professionnels. L'indentation est utilisée pour visualiser facilement quels éléments sont imbriqués dans d'autres éléments.

```html
<body>
  <p>Paragraphe 1</p>
  <div>
    <p>Paragraphe 2</p>
  </div>
</body>
```
Dans l'exemple ci-dessus, le paragraphe 1 et la balise `<div>` sont imbriqués à l'intérieur de la balise `<body>`, ils sont donc indentés de deux espaces. L'élément `Paragraphe 2` est imbriqué à l'intérieur de la balise `<div>`, de sorte qu'il est indenté de deux espaces supplémentaires.

## Commentaires
Les fichiers HTML vous permettent également d'ajouter des commentaires à votre code.

Les commentaires commencent par `<!--` et se terminent par `-->`. Tout caractère entre les deux sera ignoré par votre navigateur.

```html
<!-- Il s'agit d'un commentaire que le navigateur n'affiche pas. -->
```
L'inclusion de commentaires dans votre code est utile pour de nombreuses raisons :

- Ils vous aident (ainsi que d'autres) à comprendre votre code si vous décidez de revenir le consulter à une date ultérieure.

- Ils vous permettent d'expérimenter un nouveau code, sans avoir à supprimer l'ancien.

```html
<!-- Section des films préférés -->
<p>Liste de mes films préférés</p>
```

Dans l'exemple ci-dessus, le commentaire est utilisé pour indiquer que le texte suivant constitue une section particulière de la page.

```html
<!-- <p> Test Code </p> -->
```
Dans l'exemple ci-dessus, un élément HTML valide (un élément de paragraphe) a été "commenté". Cette pratique est utile lorsqu'il existe un code que vous souhaitez expérimenter ou si vous souhaitez y revenir plus tard.

___
| [Précédent](./9-lien-5.md)       | [Suivant (Projet)](./projet-lumières/projet-lumières.md)        |
