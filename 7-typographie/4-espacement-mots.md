# Espacement de mots

Vous pouvez également augmenter l'espacement entre les mots dans un corps de texte, techniquement appelé "espacement de mots".

Pour ce faire, vous pouvez utiliser la propriété `word-spacing`.

```css
h1 {
  word-spacing: 0.3em;
}
```

Notez qu'il est bon d'utiliser les valeurs `em` dans ce cas car `em` est dynamique - pour l'espacement des mots, il définit l'espacement en fonction de la taille de police.
Dans l'exemple ci-dessus, l'espacement entre les mots est fixé à `0,3em`.  
L'espacement par défaut entre les mots est généralement de `0,25em` et peut être défini avec la valeur normale.  
Si vous fournissez une valeur pour l'espacement entre les mots qui n'est pas normale, alors la valeur que vous fournissez est ajoutée à l'espacement par défaut.  
Par conséquent, puisque l'espacement entre les mots est fixé à `0,3em`, vos éléments `<h1>` obtiennent un total de `0,55em` d'espacement entre les mots lors du rendu.

## A vous de jouer !

1. Reprendre votre code.

2. Dans `style.css`, réglez l'espacement de mots pour les paragraphes à `1,5em`.



___
| [Précédent](./3-style-police.md)       | [Suivant](./5-espacement-lettre.md) |
