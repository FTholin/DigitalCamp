# Mise à l'échelle des arrières plans

```css
body {
  background-image: url('#');
  background-repeat: no-repeat;
  background-position: center;
  background-size: cover;
}
```

Dans l'exemple ci-dessus:

1. la première déclaration CSS définit l'image de fond (# est un caractère de remplacement pour l'URL d'une image dans cet exemple).

2. La deuxième déclaration indique au compilateur CSS de ne pas répéter l'image (par défaut, les images se répètent).

3. La troisième déclaration centre l'image dans l'élément.

4. C'est ce qui met à l'échelle l'image de fond. L'image couvrira tout l'arrière-plan de l'élément, tout en gardant l'image en proportion. Si les dimensions de l'image dépassent les dimensions du conteneur, seule une partie de l'image sera affichée.


## A vous de jouer !

1. Dans `style.css`, définissez la propriété `background-size` de `#banner` à `cover`.

___
| [Précédent](./8-echelle-image-video.md)       | [Suivant](./10-intro-reactivite.md)        |
