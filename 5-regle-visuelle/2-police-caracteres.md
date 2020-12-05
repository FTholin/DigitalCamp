# Police de caractères

Si vous avez déjà utilisé un traitement de texte formaté, il y a de fortes chances que vous ayez également utilisé une fonction qui vous a permis de changer la police de caractères que vous tapiez.
La police fait référence au terme technique "police de caractères", ou famille de polices.

Pour modifier la police de caractères du texte de votre page web, vous pouvez utiliser la propriété `font-family`.

```css
h1 {
  font-family: Garamond;
}
```

Dans l'exemple ci-dessus, la famille de polices pour tous les principaux éléments de l'en-tête a été fixée à `Garamond`.

Lorsque vous définissez les polices de caractères sur une page web, gardez les points suivants à l'esprit :
1. La police spécifiée dans une feuille de style doit être installée sur l'ordinateur d'un utilisateur afin que cette police s'affiche lorsqu'un utilisateur visite la page web.
2. La police de caractères par défaut pour tous les éléments HTML est `Times New Roman`. Vous connaissez peut-être cette police de caractères si vous avez déjà utilisé un traitement de texte formaté. Si aucun attribut de la famille de polices n'est défini, la page apparaîtra en `Times New Roman`.
3. C'est une bonne pratique de limiter à 2 ou 3 le nombre de polices de caractères utilisées sur une page web. Cela permet de charger la page plus rapidement dans certains cas et constitue généralement une bonne décision en matière de conception.
4. Lorsque le nom d'une police de caractères se compose de plusieurs mots, il est préférable de mettre le nom de la police entre guillemets, comme cela :
```css
    h1 {
      font-family: "Courier New";
    }
```

Vous trouverez [ici](https://www.cssfontstack.com) l'ensemble des références de polices de caractères sécurisées pour le web

## A vous de jouer !

1. Récupérer le code [suivant](./versions-exercices/v0-5-2/).

2. Dans le fichier CSS, ajoutez la police de caractères `Georgia` pour le titre principal `h1` ainsi que les titres secondaires `h2`.

3. Ensuite, ajoutez une règle de style pour fixer la police de caractères des paragraphes à `Helvetica`.

___

| [Précédent](./1-structure-css.md)       | [Suivant](./3-taille-police.md)        |
