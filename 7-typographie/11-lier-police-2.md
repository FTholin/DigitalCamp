# Autre façon de lier une police


Il existe d'autres moyens de lier des polices non utilisées qui ne nécessitent pas l'utilisation de la balise `<link>` dans le document HTML.
Le CSS offre un moyen d'importer des polices directement dans des feuilles de style avec la propriété `@font-face`.

Pour charger les polices avec la propriété `@font-face` :

1. Au lieu d'utiliser le lien de la police dans le document HTML, entrez le lien dans la barre d'URL du navigateur.

2. Le navigateur chargera les règles CSS. Vous devrez vous concentrer sur les règles qui sont directement étiquetées comme `/* latin */`.  
Certaines des règles latines sont sur des lignes séparées. Vous aurez besoin de chacune d'entre elles.
   
   
3. Copiez chacune des règles CSS en dessous de `/* latin */` et collez ces lignes en haut de `style.css`.  
___

> Il est important de souligner la nécessité de copier les règles `@font-face` en haut de la feuille de style pour que la police se charge correctement dans le projet.

Entraînons-nous à charger une police externe dans nos feuilles de style en utilisant la propriété `@font-face`, et à utiliser cette police pour styliser notre page.

## A vous de jouer !

1. Dans `index.html`, supprimez le lien vers la police `Space Mono` que vous avez ajouté précédemment.

2. Coller ce lien dans l'URL de votre navigateur.

3. Récupérer les deux `@font-face` sous les étiquettes `/* latin */`.

___

| [Précédent](./10-lier-polices.md)       | [Suivant (Projet)](./projet-brave-new-world/explications.md)       |
