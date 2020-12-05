# Images

Tous les éléments que vous avez appris jusqu'à présent (titres, paragraphes, listes et portées) ont un point commun :
ils sont entièrement composés de texte ! Que faire si vous souhaitez ajouter à votre page web du contenu qui n'est pas composé de texte, comme des images ?

La balise `<img>` vous permet d'ajouter une image à une page web. La plupart des éléments nécessitent des balises d'ouverture et de fermeture, mais la balise `<img>` est une balise à fermeture automatique. Notez que la fin de la balise `<img>` en bas comporte une barre oblique `/`. Les balises à fermeture automatique peuvent inclure ou omettre la barre oblique finale - les deux seront affichées correctement.
```html
<img src="image-location.jpg" />
```


La balise `<img>` possède un attribut obligatoire appelé `src`. L'attribut `src` doit être défini à la source de l'image, ou à l'emplacement de l'image. Dans ce cas, la valeur de `src` doit être le localisateur de ressources uniformes (URL) de l'image. Un URL est l'adresse web ou l'adresse locale où un fichier est stocké.

## A vous de jouer !

1. Reprendre le code précédent dument complété.

2. Sous la rubrique `Image` `<h2>`, ajoutez une image. Utilisez l'URL suivante comme source (`src`) pour l'image :
  `https://upload.wikimedia.org/wikipedia/commons/1/1f/Spirul2.jpg`


## Réflexions
1. "Une URL est l'adresse web ou l'adresse locale où un fichier est stocké". Qu'est-ce qu'une adresse locale et en quoi diffère-t-elle d'une adresse web ?
    - Une adresse locale désigne le chemin d'accès à une image, un fichier ou une ressource qui existe sur votre propre ordinateur. Une adresse web, en revanche, désigne généralement le chemin d'accès à une image, un fichier ou une ressource qui existe à l'extérieur, sur un ordinateur distant.

2. Plutôt que d'utiliser une url pour faire un lien vers des images qui existent sur le web, puis-je faire un lien vers des images qui sont stockées localement sur mon propre ordinateur ?
    - Oui, vous le pouvez ! En fait, les développeurs travaillent souvent localement avant de mettre leur code sur un site internet. Lorsqu'il s'agit d'éléments comme des images, on voudra souvent les inclure dans un dossier qui contiendra également notre document HTML. Avec une structure de répertoires ou de dossiers correctement agencée, nous pouvons créer un chemin qui pointe vers notre image et qui est relatif à notre document HTML. Dans ce scénario, ce chemin relatif sera la valeur de l'attribut `<img>` `src`.

3. Comment puis-je stocker mes propres images en ligne afin de pouvoir créer des liens vers leurs urls dans mes propres sites web ?
    - Il existe des sites qui vous permettent de télécharger vos images sur le web. Une fois votre image téléchargée, vous pouvez utiliser son adresse web comme valeur pour l'attribut `src` de l'élément `<img>`. Le plus souvent, les images et les éléments d'un projet sont stockés dans un dossier qui contient également notre document HTML. Cela permet aux développeurs de créer des chemins d'accès à utiliser comme valeurs `src` relatives au document HTML. En d'autres termes, les images et les fichiers HTML existent souvent sur le même serveur ou ordinateur.
___
| [Précédent](./12-liste-ordonnee.md)       | [Suivant](./14-attribut-alt.md)        |
