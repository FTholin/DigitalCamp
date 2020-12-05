# Mise à l'échelle image et vidéo

De nombreux sites web contiennent une variété de médias différents, comme des images et des vidéos. 
Lorsqu'un site web contient de tels médias, il est important de s'assurer qu'il est proportionné de manière à ce que les utilisateurs puissent le visualiser correctement.

```css
.container {
  width: 50%;
  height: 200px;
  overflow: hidden;
}

.container img {
  max-width: 100%;
  height: auto;
  display: block;
}
```

Dans l'exemple ci-dessus, `.container` représente une div container.
Il est réglé sur une largeur de `50%` (la moitié de la largeur du navigateur, dans cet exemple) et une hauteur de 200 pixels.
Définir la propriété de débordement `overflow` à `hidden` garantit que tout contenu dont les dimensions sont supérieures à celles du conteneur sera caché.

La seconde règle CSS garantit que les images s'adaptent à la largeur du conteneur. La propriété hauteur est fixée sur `auto` ce qui signifie que la hauteur d'une image va automatiquement s'échelonner proportionnellement à la largeur. Enfin, la dernière ligne affichera les images comme des éléments de niveau bloc (plutôt que bloc en ligne, leur état par défaut). Cela empêchera les images de s'aligner sur d'autres contenus de la page (comme le texte), ce qui pourrait ajouter une marge involontaire aux images.

Il vaut la peine de mémoriser tout l'exemple ci-dessus. 
Il représente un modèle de conception très courant utilisé pour mettre à l'échelle les images et les vidéos de manière proportionnelle.

**Note** : L'exemple ci-dessus met à l'échelle la largeur d'une image (ou d'une vidéo) à la largeur d'un conteneur. Si l'image est plus grande que le conteneur, la partie verticale de l'image débordera et ne s'affichera pas. Pour changer ce comportement, vous pouvez régler la propriété `max-height` à `100%` et `width` à `auto` (essentiellement l'échange des valeurs). La hauteur de l'image sera ainsi mise à l'échelle avec la hauteur du conteneur. Si l'image est plus grande que le conteneur, la partie horizontale de l'image débordera et ne s'affichera pas.

## A vous de jouer !

1. Regardez les images sur la page web. Remarquez qu'elles s'affichent actuellement de manière incorrecte (trop grandes). Réglons ce problème.
    - Tout d'abord, dans style.css, réglez la propriété `.image-container` à `hidden`.
    - Regardez à nouveau les images. À ce stade, les images s'affichent partiellement. En réalité, nous les avons limitées aux dimensions de leur conteneur (`.image-container`) Toute partie de l'image qui déborde du conteneur sera cachée à la vue. Cela nous permettra de les mettre à l'échelle proportionnellement.

2. Redimensionnez la largeur du navigateur dans un sens ou dans l'autre. Remarquez que les images s'agrandissent et se contractent pour montrer plus (ou moins) de l'image. Au lieu de cela, affichons l'image complète à tout moment.
    - Dans `style.css`, réglez la largeur maximale de `.image-container img` à `100%`. Cela permettra de garantir que l'image complète sera toujours affichée.

3. Nickel ! Il faut s'assurer que les images restent automatiquement proportionnelles lorsque le navigateur est redimensionné.
    - Définir la hauteur sur `auto` pour `.image-container img`.
    
4. Fixer la propriété `display` sur `block`. Cela indiquera aux images de se comporter comme des éléments de niveau bloc et facilitera la mise à l'échelle (par opposition à leur comportement en ligne par défaut).

___
| [Précédent](./7-hauteur-min-max.md)       | [Suivant](./9-echelle-arrière-plan.md)        |
