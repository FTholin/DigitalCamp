# Balise Name

Le CSS peut sélectionner des éléments HTML en utilisant le nom de la balise d'un élément. Un nom de balise est le mot (ou le caractère) entre les crochets HTML.

Par exemple, en HTML, la balise d'un élément de paragraphe est `<p>`. La syntaxe CSS pour sélectionner les éléments `<p>` est :

```css
p {

}
```

Dans l'exemple ci-dessus, tous les éléments de paragraphe seront sélectionnés à l'aide d'un sélecteur CSS. Le sélecteur dans l'exemple ci-dessus est `p`. Notez que le sélecteur CSS correspond à la balise HTML pour cet élément, mais sans les crochets d'angle.

En outre, deux accolades suivent immédiatement le sélecteur (une accolade d'ouverture et une accolade de fermeture, respectivement). Toutes les propriétés CSS seront placées à l'intérieur des accolades pour donner un style aux éléments sélectionnés.

## A vous de jouer !

1. Reprendre votre code.

2. Ajoutez un sélecteur pour les éléments `<h1>`.

3. A l'intérieur des parenthèses du sélecteur `h1` que vous venez de déclarer, écrivez :
   ```css
    color: maroon;
   ```

Ce code rendra la couleur du texte de toutes les balises `<h1>` marron.

## Réflexions

1. En CSS, pouvons-nous sélectionner n'importe quel élément HTML en utilisant son nom de balise, comme le démontre cet exercice ? Pourrais-je même créer des sélecteurs pour cibler les éléments HTML dans l'en-tête d'un document (dans les balises `<head>`) ?
     + Non. Le CSS est utilisé pour le style de nos pages. Comme le contenu des balises `<head>` n'est pas visible sur la page elle-même, nous ne pouvons pas cibler ces métadonnées avec des sélecteurs de balises.

___

| [Précédent](./4-lier-fichier-css.md)       | [Suivant](./6-attribut-classe.md)        |
