# Balise \<head\>

Jusqu'à présent, vous avez fait deux choses pour créer correctement le fichier :

- Déclarer au navigateur que votre code est HTML avec `<!DOCTYPE html>`

- Ajout de l'élément HTML (`<html>`) qui contiendra le reste de votre code.

Nous avons ajouté ces éléments à la page Spiruline que vous avez créée précédemment. Maintenant, donnons aussi au navigateur quelques informations sur la page elle-même. Nous pouvons le faire en ajoutant un élément `<head>`.

Vous vous souvenez de la balise `<body>`? <br>
L'élément `<head>` fait partie de cette métaphore HTML. Il se trouve au-dessus de notre élément `<body>`.

L'élément `<head>` contient les métadonnées d'une page web. Les métadonnées sont des informations sur la page qui ne sont pas affichées directement sur la page web. Contrairement aux informations contenues dans la balise `<body>`, les métadonnées de l'élément head sont des informations sur la page elle-même. Vous en verrez un exemple dans le prochain exercice.

Les balises d'en-tête d'ouverture et de fermeture apparaissent généralement comme le premier élément après votre première balise HTML :

```html
<head>
</head>
```

## A vous de jouer

1. Reprendre le code du projet spiruline duement complété au **chapitre 14** sur **l'attribut alt**
2. Placez l'élément `<head>` sous la balise d'ouverture `<html>`.

## Réflexions

1. Pourquoi le navigateur a-t-il besoin de métadonnées sur la page ?
    - Il existe différentes catégories de métadonnées, mais le plus souvent, les métadonnées sont des "données sur des données". Bien que le navigateur n'ait pas besoin de la plupart des métadonnées, il les utilise souvent pour améliorer l'expérience de l'utilisateur d'une manière ou d'une autre. Les métadonnées ne sont pas affichées sur une page mais en coulisses ; elles peuvent être utilisées par d'autres logiciels (crawlers, moteurs de recherche, navigateurs, etc.) pour traiter, coder, extraire ou indexer toutes sortes d'informations intéressantes (coordonnées géographiques, événements du calendrier, coordonnées de contact, etc.) De plus, les entreprises sont souvent intéressées par l'utilisation des métadonnées pour améliorer le référencement ou l'optimisation pour les moteurs de recherche.
___

| [Précédent](./2-balise-html.md)       | [Suivant](./4-titre-page.md)        |
