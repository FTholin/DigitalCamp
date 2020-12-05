# Image de fond

Le CSS a la capacité de modifier l'arrière-plan d'un élément. Une option consiste à faire de l'arrière-plan d'un élément une image.
Cela se fait par le biais de la propriété CSS `background-image`. 
Sa syntaxe ressemble à ceci :

```css
.main-banner {
  background-image: url("https://www.example.com/image.jpg");
}
```

1. La propriété `background-image` définira l'arrière-plan de l'élément pour afficher une image.

2. La valeur fournie à `background-image` est une url. L'url doit être l'url d'une image. L'url peut être un fichier de votre projet, ou un lien vers un site externe. Pour créer un lien vers une image à l'intérieur d'un projet existant, vous devez fournir un chemin de fichier relatif. S'il y avait un dossier d'image dans le projet, avec une image nommée `mountains.jpg`, le chemin de fichier relatif ressemblerait à :

```css
.main-banner {
  background-image: url("images/mountains.jpg");
}
```

## A vous de jouer !

1. Reprendre votre code.

2. Changer l'image de fond de la classe `.image`.  
   Utilisez l'URL suivante :
  `https://cdn.generationvoyage.fr/2020/05/montagnes-france.jpg`
___

| [Précédent](./7-opacite.md)       | [Suivant (Projet)](./portefolio-sean/explications.md)        |
