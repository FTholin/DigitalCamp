# Transformation de texte

Le texte peut également être stylisé pour apparaître en `majuscules` ou en `minuscules` avec la propriété `text-transform`.

```css
h1 {
  text-transform: uppercase;
}
```

Le code dans l'exemple ci-dessus formate tous les éléments `<h1>` qui doivent apparaître en majuscules.
La valeur `lowercase` peut également être utilisée pour formater le texte en minuscule.
___
## Réflexion
Comme le texte peut être directement tapé en majuscule ou en minuscule dans un fichier HTML, quel est l'intérêt d'une règle CSS qui permet de formater les lettres en majuscules ?

En fonction du type de contenu qu'une page web affiche, il peut être judicieux de toujours mettre en forme un élément spécifique dans toutes les lettres majuscules ou minuscules.
Par exemple, un site web qui rapporte des nouvelles de dernière minute peut décider de formater tous les éléments d'en-tête `<h1>` de manière à ce qu'ils apparaissent toujours en majuscules, comme dans l'exemple ci-dessus.
Cela éviterait également de mettre du texte en majuscules dans le fichier HTML, ce qui pourrait rendre le code difficile à lire.


## A vous de jouer !

1. Reprendre votre code.

2. Dans `style.css`, transformez le texte du titre principal (`h1`) pour qu'il apparaisse en majuscule.

___

| [Précédent](./5-espacement-lettre.md)       | [Suivant](./7-alignement-texte.md)       |
