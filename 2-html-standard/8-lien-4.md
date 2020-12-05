# Lier à volonté
Vous avez probablement visité des sites web où tous les liens n'étaient pas constitués de texte. Peut-être que les liens sur lesquels vous avez cliqué étaient des images ou une autre forme de contenu.

Jusqu'à présent, nous avons ajouté des liens qui n'étaient composés que de texte, comme les suivants :
```html
<a href="https://fr.wikipedia.org/wiki/Wikipédia:Accueil_principal" target="_blank">Wikipédia</a>
```
Cependant, les liens textuels seulement réduiraient considérablement votre flexibilité en tant que développeur web !

Heureusement, le HTML vous permet de transformer presque n'importe quel élément en un lien en l'entourant d'un élément d'ancrage. Avec cette technique, il est possible de transformer des images en liens en enveloppant simplement l'élément `<img>` avec un élément `<a>`.

```html
<a href="https://fr.wikipedia.org/wiki/Wikipédia:Accueil_principal" target="_blank">
    <img src="https://upload.wikimedia.org/wikipedia/commons/d/d1/Wikipedia-logo-v2-fr.svg" alt="Page Wikipédia"/>
</a>
```

Dans l'exemple ci-dessus, l'image a été transformée en lien en enveloppant l'extérieur de l'élément `<img>` avec un élément `<a>`.

## A vous de jouer !

1. Reprendre votre code duement complété.

2. Dans `index.html`, transformez l'image de votre page en un lien en enveloppant l'élément image avec un élément d'ancrage. Définissez l'attribut target de manière à ce que le lien s'ouvre dans une nouvelle fenêtre.
    - Votre élément image doit être une balise imbriquée dans votre élément d'ancrage.
    - Utilisez la même URL qu'auparavant.
___

| [Précédent](./7-lien-3.md)       | [Suivant](./9-lien-5.md)        |
