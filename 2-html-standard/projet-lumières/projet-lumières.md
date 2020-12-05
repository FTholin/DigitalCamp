# Opération Illuminations

Votre ami Denis est passioné de photos et d'évènements populaires locaux, et il vous a demandé de lui construire un nouveau site web, juste à temps pour la Fête des Lumières !

Utilisez vos nouvelles connaissances en HTML pour créer la structure sous-jacente du site. Veillez à inclure beaucoup d'images, de liens, de listes et d'autres éléments HTML que vous avez appris afin que de rendre la page attirante.
Vous pouvez visualiser le projet terminé et voir visualiser votre progression !


## A vous de jouer !

1. Pour commencer,ajoutez la déclaration `<!DOCTYPE html>` comme toute première ligne de code en haut du fichier `index.html`. Ajoutez l'élément `<html>` en dessous.

2. Sous la balise d'ouverture `<html>`, ajoutez un élément `<head>`. Sous l'élément `<head>`, ajoutez l'élément `<body>`.


3. Dans les balises `<head>`, ajoutez un élément `<title>`. Intitulez le site web "Denis célèbre le 8 décembre !".

4. Directement sous la balise d'ouverture `<body>`:
    - Ajoutez un `<h1>` qui dit "The Fête des Lumières !"
    - En dessous, ajoutez un `<h2>` qui dit : "Conseils avant de partir à la découverte des œuvres lumière"
    - En dessous, ajoutez un `<h2>` qui dit : "LES ŒUVRES LUMIÈRE"

5. Sous la première balise d'en-tête, créez une liste non ordonnée.

La liste non ordonnée doit comporter les trois éléments suivants :
  - Habillez-vous chaudement et confortablement : bonnet, écharpe, doudoune, gants et de bonnes chaussures de marche !
  - Préparez votre balade à l’avance en vous concoctant une sélection d'oeuvres ou en suivant les parcours proposés.
  - Téléchargez l’appli mobile Fête des Lumières pour Android ou iOS, bien utile pour se repérer en centre-ville.
  
    
7. Après la dernière balise `<h2>`, ajoutez un dernier paragraphe qui dit:
"Sur la place des Célestins, Lightning Cloud de Jérôme Donna est un véritable enchantement. Son nuage lumineux donne une impression de relief saisissante. S'il n'y avait qu'une seule oeuvre à voir, c'est celle-là !".

Bien sûr, ce ne serait pas un blog de mode sans quelques images. Au-dessus de chaque paragraphe, ajoutez une balise <img> et définissez son src comme étant l'un des liens suivants :
    - `https://upload.wikimedia.org/wikipedia/commons/3/3a/F%C3%AAte_des_Lumi%C3%A8res_-_Lyon_%282008%29.JPG` avec une taille de `240` hauteur x `320` largeur
    - `https://upload.wikimedia.org/wikipedia/commons/3/30/TCL-crowd.JPG` avec une taille de `240` hauteur x `320` largeur
    - `https://upload.wikimedia.org/wikipedia/commons/5/57/Lumignons_fete_des_Lumieres_Lyon_8-12-2013.jpg` avec une taille de `240` hauteur x `320` largeur

Votre premier billet sur la fête est complet !

Ajoutons maintenant une image de Denis, pour que ses lecteurs apprennent à la connaître.

8. Sous la balise d'ouverture du corps, ajoutez une balise  avec la source suivante :
    - `https://upload.wikimedia.org/wikipedia/commons/6/68/PeterLik.jpg`

9. Sous le tag `<img>`, ajoutez un `<h3>` qui dit "by Denis | il y a 1 jour"

Denis veut que ses lecteurs sachent qu'elle a écrit beaucoup plus qu'un seul billet. Faisons une liste de quelques articles similaires.

10. Sous le dernier paragraphe, ajoutez une balise `<h4>` qui dit "Articles similaires".
    Sous cette balise d'en-tête, créez une liste non ordonnée.

La liste non ordonnée doit comporter les quatre éléments suivants :
    - `SaintéLyon une aventure !`
    - `Nuits Sonores`
  

11. Relions l'article de Denis au reste du web ! 
Dans le premier paragraphe, transformez "Lyon" en lien et envoyez-le à : `https://fr.wikipedia.org/wiki/Lyon` . 
Veillez à inclure l'attribut target="_blank" pour qu'il s'ouvre dans une nouvelle page.

Denis veut s'assurer que ses amis puissent la contacter.

12. Au bas de votre corps, ajoutez un nouveau <div> et définissez son id="contact".

13. À l'intérieur d'un paragraphe, créez une nouvelle balise et placez-y les informations de contact suivantes :
    - `email: denis.p@openworld.com | tel: 06-52-12-16-89-09 | adresse: 10 Rue des Antonins Villeurbanne`

A l'intérieur du contact `<div>`, mettez des balises `<strong>` d'ouverture et de fermeture autour de "email", "téléphone" et "adresse".

Faisons de la photo de profil un lien vers la section "contact" de la page web.

Trouvez la balise `<img>` du profil, et entourez-la en ouvrant et en fermant les balises `<a>`.
Dans la balise `<a>`, mettez href="#contact".
___
  

| [Précédent](./1-introduction.md)       |   [Quiz](https://moodle.ucly.fr/20-21/mod/quiz/view.php?id=32981)  | [Suivant : 3-table-html](../../3-table-html/1-prise-en-main.md)        |


