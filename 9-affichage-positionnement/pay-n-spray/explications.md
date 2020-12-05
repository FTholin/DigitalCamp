# Projet Pay'N'Spray

Dans ce projet, vous utiliserez des propriétés telles que l'affichage et la position pour améliorer la mise en page de la page d'accueil d'une société de design fictive, Pay'N'Spray.

Le site comporte quelques règles de style pour commencer. Vous améliorerez la disposition et le positionnement du menu de navigation en haut de la page et des trois sections d'appui (Réparation, Anonymisation) en dessous de l'image.

1. Récupérer le code [suivant](./start).

2. L'entête `<header>` défile actuellement avec le reste du document.
    - Définissez la propriété `position` de manière à ce qu'elle reste collée en haut de la fenêtre lorsque le document défile.


3. L'entête `<header>` a rétréci !
    - Modifiez la largeur d'un même élément de manière à ce qu'il s'étende sur tout son élément parent.

4. Les éléments de liste (`<li>`) à l'intérieur de la section de navigation (`<nav>`) sont actuellement affichés sous forme de liste.
    - Définissez la propriété `display` de manière à ce qu'ils puissent apparaître les uns à côté des autres horizontalement
> inline-block permettra aux éléments `<li>` de se positionner horizontalement sur une même ligne et vous permettra de régler leur largeur.
    - Sélectionnez les éléments à l'aide du sélecteur `nav li`.
  
5. Fixez la largeur des mêmes éléments à 80 pixels.

6. Après avoir fixé la `position` de l'élément `<header>` à `fixed`, le contenu de l'ensemble du site s'est déplacé vers le haut.
    - Définissez la position de `<main>` de manière à pouvoir le positionner de manière `relative`.
    


7. L'élément `<header>` a disparu derrière l'élément `<main>`.
   - Utilisez la propriété `z-index` pour rendre `<header>` visible.
   

8. La bar semble bien positionné, cependant elle fixe `title` en haut de la page.
    - Décalez l'élément `<main>` de 80 pixels à partir du haut.
    

9. Maintenant, fixez le style de l'élément sous l'image.
    - Ajoutez une déclaration au sélecteur `.supporting .col` pour que ces éléments puissent apparaître horizontalement les uns à côté des autres, mais avec une `height` et une `width` définies.
    
10. Les éléments `.supporting .col` ne semblent pas se placer horizontalement. 
    -  Définissez la largeur et la hauteur de ces éléments à 200 pixels.




___
| [Précédent](./11-clear.md)       | [Quiz](https://moodle.ucly.fr/20-21/mod/quiz/view.php?id=32988)  |   [Suivant](../../10-conception-reactive/1-mesures-relatives.md)       |
