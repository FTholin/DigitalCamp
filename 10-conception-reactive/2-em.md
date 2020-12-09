# Em

L'intégration de la taille relative commence par l'utilisation d'unités autres que les pixels. Une unité de mesure que vous pouvez utiliser dans le CSS pour créer un contenu de taille relative est l'`em`, écrit comme em dans le CSS.

Historiquement, l'`em` représentait la largeur d'une lettre majuscule M dans la police de caractères et la taille utilisées. Ce n'est plus le cas aujourd'hui.

Aujourd'hui, l'`em` représente la taille de la police de base utilisée.  
Par exemple, si la police de base d'un navigateur est de 16 pixels (ce qui est normalement la taille par défaut du texte dans un navigateur), alors 1 em est égal à 16 pixels.
2 ems équivaudraient à 32 pixels, et ainsi de suite.

Examinons deux exemples qui montrent comment les em peuvent être utilisés dans le CSS.

```css
.heading {
  font-size: 2em;
}
```

Dans l'exemple ci-dessus, aucune police de base n'a été spécifiée, donc la taille de la police de l'élément d'en-tête `heading` sera définie par rapport à la taille de la police par défaut du navigateur.
En supposant que la taille de la police par défaut est de 16 pixels, la taille de la police de l'élément `heading` sera de 32 pixels.

```css
.splash-section {
  font-size: 18px;
}

.splash-section h1 {
  font-size: 1.5em;
}
```

L'exemple ci-dessus montre comment utiliser `em` sans se fier à la taille de police par défaut du navigateur.
Au lieu de cela, une taille de police de base (18px) est définie pour tout le texte dans l'élément `splash-section`.
La deuxième règle CSS définira la taille de la police de tous les éléments `h1` à l'intérieur de  `splash-section` par rapport à la police de base de `splash-section` (18 pixels).
La taille de police résultante des éléments `h1` sera de *27 pixels*.


## A vous de jouer !

1. Reprendre le code [suivant](./versions-exercices/v0-10-1/).

2. Dans `style.css`, réglez la taille de la police dans `#banner h1` ("Voyage Manchester") à `1.5em`.

3. Réglez la taille de police de `.post h2` ("Les coins des artistes") à `1.75em`.

4. Définissez la taille de police `.post h3` à `1.25em`.

5. Définissez la taille de police dans le pied de page `footer` (`"&copy ; Week-end en famille à Manchester-Madame Oreille-https://www.madame-oreille.com/week-end-famille-a-manchester/"`) à `0.75em`.


___
| [Précédent](./1-mesures-relatives.md)       | [Suivant](./3-rem.md)       |
