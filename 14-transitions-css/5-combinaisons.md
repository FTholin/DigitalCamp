# Combinaisons

La règle de transition abrégée présente un avantage par rapport à l'ensemble des règles de transition : vous pouvez décrire des transitions uniques pour plusieurs propriétés, et les combiner.

Pour combiner les transitions, ajoutez une virgule (`,`) avant le point-virgule (` ;`) dans votre règle.
Après la virgule, utilisez la même syntaxe raccourcie

```css
{
  transition: color 1s linear,
  font-size 750ms ease-in 100ms;
}
```

Le code ci-dessus fait la transition entre deux propriétés à la fois. La couleur du texte change en une seconde en temps linéaire et sans retard. Dans le même temps, la taille de la police passe de 750 millisecondes à 100 millisecondes. Ce "chaînage" est un outil puissant pour exprimer des animations compliquées.

## A vous de jouer !

1. Reprenez le code [suivant](exercices-versions/v0-14-5/).

2. Lorsque vous passez la souris sur le bouton du navigateur, vous remarquerez qu'il change instantanément. Réglons ce problème de manière à ce que le changement soit animé.
  Faites une nouvelle déclaration CSS dans style.css pour cibler tous les éléments du bouton. Il y a trois types d'éléments à prendre en compte, `<span>`, `<div>`, and `<i>` :

```css
  .button span,
  .button div,
  .button i {
 
  }
```

3. Dans la nouvelle déclaration, ajoutez une règle d'abréviation afin de modifier la largeur de tous les éléments.
`transition: width 750ms ease-in 200ms;`

4. Cela a l'air plus agréable, sauf que le texte "TELECHARGER" disparaît instantanément. Animons cela en tandem.
  Ajoutez une virgule et une autre valeur de transition pour la propriété `left`.
  Faites en sorte que la durée soit de 500 ms, la fonction `ease-out`, et le délai de `450ms`.
> `transition: width 750ms ease-in 200ms, left 500ms ease-out 450ms;`

___
| [Précédent](./4-abreviation.md)       | [Suivant (projet)](./jules-verne/explications.md)    |
