# Lier les polices

Lorsque nous avons le lien vers la police de notre choix, nous pouvons ajouter la police à la section `<head>` du document HTML, en utilisant la balise `<link>` et le `href`.

Voyons quelques exemples :

1. Une seule police liée, en utilisant `Droid Serif`. Exemple :

    ```html
    <head>
      <link href="https://fonts.googleapis.com/css?family=Droid%20Serif" type="text/css" rel="stylesheet">
    </head>
    ```

2. Plusieurs polices liées, en utilisant les polices `Droid Serif` et `Playfair Display`. Notez la présence du caractère `|`. Exemple :

    ```html
    <head>
      <link href="https://fonts.googleapis.com/css?family=Droid%20Serif|Playfair%20Display" type="text/css" rel="stylesheet">
    </head>
    ```

3. Plusieurs polices liées, ainsi que des poids et des styles. Ici, `Droid Serif` a des poids de police de `400`, `700` et `700i`, tandis que `Playfair Display` a des poids de police de `400`, `700` et `900i` :

    ```html
    <head>
      <link href="https://fonts.googleapis.com/css?family=Droid%20Serif:400,700,700i|Playfair%20Display:400,700,900i" rel="stylesheet">
    </head>
    ```

Une fois qu'une police est liée, nous pouvons créer des sélecteurs CSS pour cibler les éléments, tout comme nous le faisons avec d'autres polices.

## A vous de jouer !

1. Dans votre `index.html`, incluez la police `Space Mono` dans le projet en utilisant la balise `<link>`.

___

| [Précédent](./9-empattement.md)       | [Suivant](./11-lier-police-2.md)        |
