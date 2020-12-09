# Attribut Alt

Certains éléments HTML possèdent un attribut intégré appelé `alt` qui fonctionne comme la propriété `aria-label` mais qui possède des fonctionnalités supplémentaires.

L'attribut alt est utilisé pour décrire une image (ou plusieurs autres éléments). Un lecteur d'écran lira la valeur de l'attribut `alt` à haute voix. Toutefois, si l'élément ne peut être vu visuellement - que ce soit parce que l'utilisateur est malvoyant, qu'une source incorrecte est référencée ou que la page est consultée par une connexion lente - l'attribut `alt` sera affiché à sa place.

En revanche, la valeur de `aria-label` ne sera jamais affichée à l'écran et constitue un meilleur choix pour les éléments qui ne prennent pas en charge l'attribut `alt`.

```html
<img src="#" alt="a kitten snuggling a puppy"/>
```

Dans l'exemple ci-dessus, un lecteur d'écran lira à haute voix "image : un chaton câlinant un chiot" à l'utilisateur. Si l'image ne se charge pas correctement, le navigateur affichera ce texte sous forme d'info-bulle.

Lorsque vous utilisez l'attribut `alt`, vous devez respecter ces conventions :

- La valeur de `alt` doit décrire l'image de façon concise.
- Pour les images qui sont également des éléments `<a>`, l'attribut `alt` doit décrire la source que le lien cible.
- Si une image ne contient aucune information (comme une bordure décorative), l'attribut `alt` doit être vide, mais ne doit jamais être omis.
- Si une image est décrite par du texte à proximité de l'image, ne dupliquez pas la description dans l'attribut `alt`. Utilisez plutôt un attribut `alt` vide.
- La valeur d'un attribut `alt` ne doit pas dépasser **150 caractères**.

## A vous de jouer !

1. Reprendre votre code.
2. Donnez à l'image d'Ada Lovelace un attribut `alt` avec la valeur `Ada Lovelace`.

___ 
| [Précédent](./4-proprietes-aria.md)   | [Suivant : 12-doc](../12-doc/1-doc-css.md)   |
