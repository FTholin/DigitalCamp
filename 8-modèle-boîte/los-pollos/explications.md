# Los Pollos Hermanos

Dans le cadre de ce projet, vous suivrez des instructions étape par étape pour réparer le site web d'un restaurant fictif.
Tout le HTML et la plupart des CSS sont intacts, mais les propriétés du modèle de boîte n'ont pas encore été définies.
Vous utiliserez vos connaissances en matière de `height`, `width`, `padding`, `border` et de `margin` pour mener à bien ce projet.

Les fichiers `index.html` et `style.css` existants du site web sont fournis.
La plupart des éléments pour lesquels vous devrez ajouter des styles ont déjà des ensembles de règles dans `style.css` auxquels vous pouvez ajouter des déclarations supplémentaires.

## A vous de jouer !

1. Reprendre le code [suivant](./start/style.css):

2. Vous allez parcourir le menu de Los Pollos Hermanos de haut en bas. Commençons par styliser l'élément `<nav>` contenant le logo et les éléments de navigation.
    - Réglez `width` de `img` à 180 pixels.
    - Centrez `img` horizontalement en utilisant la propriété `margin`.
    


2. Déinissez la marge des éléments `span` à l'intérieur de `nav` sur 10 pixels de haut et en bas, et sur 0 pixel de gauche et à droite.



3. Définissez maintenant quelques règles pour l'élément de classe `content`. Cet élément est un conteneur pour tous les éléments non inclus dans `<nav>`.
    - Fixer la hauteur à 500 pixels.
    - Créez des marges verticales de 10 pixels et des marges horizontales automatiques.
    - Définissez les éléments `.body` à l'intérieur de `.content` de manière à ce qu'il n'y ait pas de marge verticale et que les marges horizontales soient automatiquement centrées.


définition des marges supérieures et inférieures de 240 pixels et attribution automatique des marges horizontales.

4. Avec une hauteur de 500 pixels pour `.content`, certains éléments débordent de leur boîte si la fenêtre du navigateur est trop petite.
  - Rendre `.content` déroulante avec la propriété `overflow`.
  - Redimensionnez la fenêtre du navigateur afin qu'elle soit très fine et notez que cette section est maintenant déroulante.
  

5. Il est maintenant temps de s'attaquer à l'en-tête `.header` et à son élément `h1`: "POULET FRIT".
  - Définissez la hauteur de la classe `.header` à 320 pixels.
  - Créez un rembourrage de 20 pixels pour l'élément `h1` à l'intérieur de l'en-tête `.header`.
  - Définissez les marges verticales à 0 pixel et les marges horizontales à déterminer automatiquement pour le même élément `h1`.
  
6. Ajoutez maintenant un modèle de boîte à l'élément `.button` nommé "COMMANDEZ MAINTENANT" . À chaque modification, veillez à faire défiler vers le bas si nécessaire pour voir l'effet sur le bouton.
  - Réglez la largeur à 200 pixels.
  - Réglez le rembourrage à 20 pixels.
  - Réglez les marges verticales sur 40 pixels et les marges horizontales sur automatique.
  - Donnez au bouton une bordure `#fcd93b` solid de 1 pixel.
  
7. Enfin concentrons nous sur les faits nutritifs de la section `nutrition` en bas de la page.
  - Définissez le rembourrage de l'élément `ul.nutrition` à 20 pixels.
  - Définissez la largeur des éléments `li` dans `ul.nutrition` à 200 pixels.
  - Réglez un rembourrage vertical de 10 pixels et un rembourrage horizontal de 20 pixels sur les mêmes éléments.
  - Ajoutez une marge inférieure de 3 pixels aux mêmes éléments.
 

Bon travail : ce menu est très bien présenté, et la disposition et l'espacement sont beaucoup plus lisibles. Si vous le souhaitez, vous pouvez continuer à peaufiner le design ou ajouter votre propre style !

___


| [Précédent](./12-changer-modèles-boîte.md)       |   [Quiz](https://moodle.ucly.fr/20-21/mod/quiz/view.php?id=32987)   |  [Suivant : 9-affichage-positionnement](../../9-affichage-positionnement/1-intro-positionnement.md) |
