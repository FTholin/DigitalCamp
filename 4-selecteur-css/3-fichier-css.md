# Fichier CSS

Les développeurs évitent de mélanger le code en stockant le code HTML et le code CSS dans des fichiers séparés (les fichiers HTML ne contiennent que le code HTML, et les fichiers CSS ne contiennent que le code CSS).

Vous pouvez créer un fichier CSS en utilisant l'extension de nom de fichier `.css`, comme suit : `style.css`

Avec un fichier CSS, vous pouvez écrire tout le code CSS nécessaire au style d'une page sans sacrifier la lisibilité et la maintenabilité de votre fichier HTML.

## A vous de jouer !

1. Jetez un coup d'œil au fichier HTML. Coupez le code CSS entre les balises d'ouverture et de fermeture `<style>` et collez-le directement dans le fichier CSS.

2. Veillez à supprimer l'élément `<style>` restant (maintenant vide) du fichier HTML.


## Réflexions

1. Quelle est la meilleure façon d'inclure le CSS dans un projet ? Comment savoir quand
Utiliser les styles en ligne, les balises ou un fichier `.css` ?

    - En tant que développeur web, vous finirez par tomber sur des documents HTML qui incluent des CSS soit en ligne avec des attributs de style, soit dans les balises `<style>` en tête du document. Il est donc important de connaître les différentes façons d'inclure du CSS dans un projet.

    - Cela étant dit, il n'est pas très habituel de mélanger HTML et CSS. En tant que développeurs, nous voulons "séparer nos préoccupations" car cela crée généralement des bases de code plus souples, plus lisibles et plus faciles à maintenir. Ainsi, le fait de conserver notre CSS dans un fichier .css séparé est la meilleure façon d'inclure le CSS dans la plupart des projets.

2. Comment puis-je lier mon HTML et mon CSS ?

    - Lier HTML et CSS peut être délicat dans vos premiers projets, et il n'est pas rare de devoir se battre un peu pour y parvenir. Essayez d'inclure le code suivant dans la tête de votre projet HTML.

    - `<link rel="stylesheet" href="chemin/mon_fichier_css.css">` vous devez indiquer à votre navigateur où trouver le fichier CSS. Il peut s'agir d'un lien absolu ou relatif. En général, votre fichier CSS se trouve dans un répertoire de ressources et un sous-répertoire css.

___

| [Précédent](./2-balise-style.md)       | [Suivant](./4-lier-fichier-css.md)        |
