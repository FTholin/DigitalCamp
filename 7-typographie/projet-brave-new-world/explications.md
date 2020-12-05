# Brave New World

Écrivain britannique, Aldous Huxley a écrit de nombreux livres et essais de science-fiction. Il est notamment l'auteur du Meilleur des mondes, des Portes de la perception et de L'Art de voir. Vous allez modifier la typographie de son site pour la promotion du Meilleur des Mondes, en changeant la taille, le style et les familles de polices, pour rendre la page plus lisible.

Grâce à votre compréhension de la typographie, aidez Aldous Huxley à améliorer la lisibilité de son site pour ses lecteurs.

1. Récupérer le code [suivant](./start)

2. La section d'en-tête du site d' Aldous Huxley contient le nom de l'auteur, ainsi que le texte "OEUVRES" et "CONTACT".
    - Changez la propriété `font-weight` de `header` pour que le texte apparaisse en gras.


3. En se déplaçant vers le bas de la page, la section de la bannière (`banner`) contient une image étonnante, deux blocs de texte, une balise `h2` avec le texte `"1932"`, et une balise `h1` avec le texte `"Le Meilleur des mondes"`.

    - Donnez à la balise `h2` une épaisseur de `500` et à la balise `h1` une épaisseur de `900`.


4. Après avoir examiné le projet, l'auteur suggère que la hauteur de ligne (`line-height`) semble un peu décalée et doit être modifiée tout au long de la page.
    - Fixez la hauteur de ligne des éléments de la page suivante selon les recommandations :
      - Le paragraphe dans la section `journal` doit avoir une hauteur de ligne de `1.4` fois la taille de la police.
      - La première lettre de la section `journal` doit avoir une hauteur de ligne (`line-height`) de `0.87` fois la taille de la police.
      - La citation `quote` doit avoir une hauteur de ligne de `1.2` fois la taille de la police.
      - Le contenu du pied de page (`footer`) doit avoir une hauteur de ligne égale à `1.5` fois la taille de la police.
 

5. Le site utilise actuellement des polices avec et sans empattement communes que l'on trouve sur les ordinateurs des utilisateurs. Depuis que l'auteur a publié le site pour la première fois, plusieurs nouvelles bibliothèques de polices ont créé des polices qui, selon vous, conviendraient mieux au site.

    - En utilisant [l'API Google Fonts](https://fonts.google.com), ajoutez les polices suivantes au fichier `index.html` :
    - `Abril Fatface`
    - `Work Sans` avec une épaisseur de `400`, `500` et `800`.
    - `Merriweather` avec une épaisseur de `400` et `400 italic`.
    
    - Vous pouvez soit lier ces polices dans une seule balise `<link>`, soit trois balises séparées.
    
6. Vous pouvez désormais utiliser les nouvelles polices de Google Fonts dans le cadre de notre projet. En vous déplaçant à nouveau vers le bas de la page, définissez la propriété des familles de police `font-family` comme recommandé :
    - Dans la section `banner`, définissez la police de la balise `<h2>` sur `Work Sans`.
    - Dans la section `banner`, définissez la police de la balise `<h1>` sur `Abril Fatface`.
    - Définissez la police de caractère de la section `journal` sur `Work Sans` 
    - Définissez la police de caractères de la légende de la photo `photo caption` sur `Merriweather`.
    
7. La page est magnifique, mais vous devez également tenir compte des utilisateurs qui ne peuvent pas accéder aux polices de Google. Trouvez leur plusieurs polices de secours à utiliser au cas où ils ne pourraient pas accéder aux polices d'un tiers :
    - Définissez les polices de secours comme suit :
      - `Arial` et `sans-serif` pour la balise `<h2>`.
      - `sans-serif` pour la section `banner`.
      - `serif` pour la section `journal`.
      - `serif` pour le seclecteur `photo-caption`.


8. Au lieu de lier la police à partir de `index.html`, vous réalisez qu'il serait préférable d'importer les polices Google dans les fichiers directement dans des feuilles de style avec la propriété `@font-face`.
    - Utilisez la propriété `@font-face` pour importer les polices directement dans les feuilles de style, et supprimez les balises `<link>` qui référencent les polices Google de la page `index.html`.
    
    - Copiez et collez la règle `@font-face` des polices fixée en `href`de votre HTML.
    Par exemple, le `href` de `Roboto` renvoie une série de règles `@font-face`. Incluez chaque police et épaisseur de police dont vous avez besoin.
    
___

| [Précédent](./11-lier-police-2.md)       |   [Quiz](https://moodle.ucly.fr/20-21/mod/quiz/view.php?id=32986)  |     [Suivant](../../8-modèle-boîte/1-boîte-intro.md)    |
