# Réinitialisation par défault

Tous les principaux navigateurs web ont une feuille de style par défaut qu'ils utilisent en l'absence d'une feuille de style externe. Ces feuilles de style par défaut sont connues sous le nom de feuilles de style de l'agent utilisateur. Dans ce cas, le terme "agent utilisateur" est un terme technique pour le navigateur.

Les feuilles de style de l'agent utilisateur ont souvent des règles CSS par défaut qui fixent des valeurs par défaut pour le remplissage et la marge. Cela affecte la façon dont le navigateur affiche les éléments HTML, ce qui peut rendre difficile pour un développeur de concevoir ou de styliser une page web.

De nombreux développeurs choisissent de réinitialiser ces valeurs par défaut afin de pouvoir réellement travailler avec une ardoise propre.

```css
* {
  margin: 0;
  padding: 0;
}
```

Le code de l'exemple ci-dessus réinitialise les valeurs de marge et de remplissage par défaut de tous les éléments HTML.
Il s'agit souvent de la première règle CSS dans une feuille de style externe.

Notez que ces deux propriétés sont toutes deux définies à 0. Lorsque ces propriétés sont définies à 0, elles ne nécessitent pas d'unité de mesure.

## A vous de jouer !

1. Reprendre votre code.
2. Dans `style.css`, réinitialiser les valeurs par défaut de la marge et du `padding` pour `body`. Qu'arrive-t-il à la page web dans le navigateur ?


___
| [Précédent](./9-debordement.md)       | [Suivant](./11-visibilite.md) |
