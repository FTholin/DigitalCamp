# flex-flow

Comme pour la propriété fkow, la propriété flex-flow permet de déclarer les propriétés flex-wrap et flex-direction sur une seule ligne.

```css
.container {
  display: flex;
  flex-wrap: wrap;
  flex-direction: column;
}
```

Dans l'exemple ci-dessus, nous prenons deux lignes pour accomplir ce qui peut être fait avec une seule.

```css
.container {
  display: flex;
  flex-flow: column wrap;
}
```

Dans l'exemple ci-dessus, la première valeur de la déclaration de flex-flow est une valeur de flex-direction et la seconde est une valeur de flex-wrap. Toutes les valeurs pour flex-direction et flex-wrap sont acceptées.


## A vous de jouer !

1. Reprendre le code  [suivant](./versions-exercices/v0-13-13/)

2. Dans le sélecteur `#row-reverse`, définissez la propriété `flex-flow` avec les valeurs `row-reverse` et `wrap`.

3. Dans le sélecteur `#column`, définissez la propriété `flex-flow` pour donner aux éléments une direction de `column` et de `wrap`. Vous devriez pouvoir faire cela en une seule ligne.


___
| [Précédent](./12-flex-direction.md)       | [Suivant](./14-flexbox-emboitees.md)    |
