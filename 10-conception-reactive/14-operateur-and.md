# Opérateur AND

Dans les exercices précédents, nous avons enchaîné plusieurs caractéristiques de médias du même type dans une requête de médias en utilisant l'opérateur `and`.

Il nous a permis de créer une plage en utilisant `min-width` et `max-width` dans la même requête.

L'opérateur `and` peut être utilisé pour exiger des fonctions multimédias. Par conséquent, nous pouvons utiliser l'opérateur `and` pour exiger à la fois une `max-width` de `480px` ainsi
q'une `min-resolution` de `300dpi`.

```css
@media only screen and (max-width: 480px) and (min-resolution: 300dpi) {
    /* CSS ruleset */
}
```

En plaçant l'opérateur `and` entre les deux caractéristiques médias, le navigateur exigera que les deux  soient vraies avant de rendre le CSS dans la requête de média.
L'opérateur `and` peut être utilisé pour enchaîner autant de caractéristiques médias que nécessaire.

## A vous de jouer !

1. Reprendre votre code.

2. Le texte du site doit être plus grand pour les utilisateurs qui disposent de petits écrans à faible résolution.
    - Écrire une requête média qui s'applique lorsque `max-resolution` est de `150dpi` et que l'écran a une `max-width` de `480px`.
    
3. A l'intérieur de la requête média, faites en sorte que la taille de la police de l'élément `.page-description` soit de `20px`.


___
| [Précédent](./13-ppi.md)       | [Suivant](./15-liste-separe-virgule.md)        |
