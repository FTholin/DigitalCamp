# Police de caractères

Si vous avez déjà utilisé un traitement de texte formaté, il y a de fortes chances que vous ayez également utilisé une fonction qui vous a permis de changer le **"type de police"** que vous tapiez par exemple : sur Word). L'expression **"type de police"** fait référence au terme technique **police de caractères**.

Pour changer le type de police du texte de votre page web, vous pouvez utiliser la propriété `font-family`.

```css
h1 {
  font-family: Garamond;
}
```

Dans l'exemple ci-dessus, la police de caractères pour tous les principaux éléments de l'en-tête a été fixée à Garamond.

Lorsque vous définissez les polices de caractères sur une page web, gardez à l'esprit les points suivants :

- La police spécifiée dans une feuille de style doit être installée sur l'ordinateur d'un utilisateur pour que cette police s'affiche lorsqu'un utilisateur visite la page web. 

- Vous avez probablement remarqué que nous n'avons pas spécifié de police de caractères dans les exercices précédents. Comment le navigateur sait-il exactement quelle police de caractères utiliser pour afficher la page web ? La police par défaut de nombreux navigateurs est Times New Roman.

- C'est une bonne pratique de limiter le nombre de polices de caractères utilisées sur une page web à 2 ou 3.

- Lorsque le nom d'une police de caractères est composé de plusieurs mots, il doit être mis entre guillemets (sinon il ne sera pas reconnu),

```css
h1 {
  font-family: "Courier New";
}
```


## A vous de jouer !

1. Partir du code [suivant](versions-exercices/v0-7-1/).

2. Dans le fichier `style.css`, changer la police de caractères en `Georgia` pour `h1` et `h2`.

3. Changer la police de caractères en `Helvetica` pour les paragraphes.


___

| [Précédent](../6-couleurs/4-teinte-saturation.md)       | [Suivant](./2-epaisseur-police.md)       |
