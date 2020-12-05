# Vidéos

En plus des images, le HTML permet également d'afficher des vidéos. Comme la balise `<img>`, la balise `<video>` nécessite un attribut `src` avec un lien vers la source vidéo. Toutefois, contrairement à la balise `<img>`, l'élément `<video>` nécessite une balise d'ouverture et une balise de fermeture.

```html
<video src="myVideo.mp4" width="320" height="240" controls>
  Video not supported
</video>
```

Dans cet exemple, la source vidéo (`src`) est `myVideo.mp4` La source peut être un fichier vidéo hébergé sur votre page web, ou une URL qui pointe vers un fichier vidéo hébergé sur une autre page web.

Après l'attribut `src`, les attributs `width` (largeur) et `height` (hauteur) sont utilisés pour définir la taille de la vidéo affichée dans le navigateur. L'attribut controls indique au navigateur d'inclure les commandes de base de la vidéo : pause, lecture et saut.

Le texte "`Vidéo non prise en charge`" entre les balises d'ouverture et de fermeture de la vidéo ne sera affiché que si le navigateur ne peut pas charger la vidéo.


## Réflexions

1. Le contenu textuel des balises vidéo semble se comporter de la même manière que le texte alternatif de la balise img. Par souci de cohérence, pouvons-nous utiliser un attribut `alt` avec la balise vidéo à la place ?
    - C'est une excellente observation, mais nous ne pouvons pas utiliser l'attribut alt dans la balise vidéo d'ouverture. Bien que cela puisse sembler incohérent, c'est en fait une question de conception, car nous pourrions vouloir que notre élément vidéo contienne des options de repli. Par exemple, si la vidéo ne se charge pas, nous pourrions vouloir afficher un lien vers une autre vidéo qui se charge. Comme les attributs ne peuvent pas contenir de balises, ce scénario ne serait pas possible avec les seuls attributs alt.
    - Si cette gestion de repli donne plus de contrôle au développeur, vous vous demandez peut-être pourquoi la balise `img` ne suit pas. La réponse à cette question implique des problèmes de rétrocompatibilité. En gros, ce comportement est voulu et est un choix assumé de conception.

___
| [Précédent](./1-introduction.md)       |  [Quiz](https://moodle.ucly.fr/20-21/mod/quiz/view.php?id=32980)   | [Suivant : 2-Html-Standard](../2-html-standard/1-preparation.md)        |
