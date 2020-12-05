# Div
L'un des éléments les plus populaires du HTML est l'élément `<div>`. C'est l'abréviation de "division" (un conteneur qui **divise** la page en sections). Ces sections sont très utiles pour regrouper les éléments de votre HTML.

```html
<body>
  <div>
    <h1>Pourquoi utiliser les divs?</h1>
  </div>
  <div>
    <p>Ils sont parfaits pour grouper des éléments !</p>
  </div>
</body>
```
Les `<div>` n'ont pas de représentation visuelle en soi, mais ils sont très utiles lorsque nous voulons appliquer des styles personnalisés à nos éléments HTML. Les `<div>` nous permettent de regrouper des éléments HTML pour appliquer les mêmes styles à tous les éléments HTML qu'ils contiennent. Nous pouvons également styliser l'élément `<div>` dans son ensemble.

Les `<div>` peuvent contenir du texte ou d'autres éléments HTML, tels que des liens, des images ou des vidéos. N'oubliez pas de toujours ajouter deux espaces d'indentation lorsque vous emboîtez des éléments à l'intérieur des `<div>` pour une meilleure lisibilité.

## A vous de jouer !

1. Reprendre le code de l'exercice précédent.

2. Sous le titre `<h1>` qui indique `Spiruline`, ajoutez une balise d'ouverture `<div>`. Placez la balise fermante `</div>` après l'élément `<h3>` qui dit `Bienfaits`. N'oubliez pas d'utiliser votre barre d'espacement pour ajouter deux espaces d'indentation lorsque vous emboîtez des éléments.

3. Au-dessus de l'élément `<h2>` nommé `Habitat`, ajoutez une balise d'ouverture `<div>`.
Fermez la balise `</div>` après l'élément `<h3>` qui indique `Afrique`.

4. Au-dessus de l'élément `<h2>` nommé `Image`, ajoutez une balise ouvrante `<div>`. Placez la balise de fermeture `</div>` juste au-dessus de la balise de fermeture `</body>`.

## Réflexions

1. L'ajout d'éléments `<div>` à notre document HTML ne semble pas changer quoi que ce soit à la page. Quel est l'intérêt d'imbriquer d'autres éléments dans un `<div>` ? Cela n'augmente-t-il pas simplement la complexité de notre structure HTML ?
    - Lorsqu'on utilise les balises `<div>` comme conteneurs, il est vrai que notre nidification pourrait devenir plus complexe. Cependant, l'avantage est que si nous créons une structure HTML bien pensée, nous pouvons plus facilement analyser et cibler le contenu correspondant. En d'autres termes, il y a souvent un compromis entre la complexité et la lisibilité ou la ciblabilité. En tant que développeurs, nous voulons trouver le bon équilibre entre la création d'une structure suffisamment cohérente pour améliorer la lisibilité et la ciblabilité sans nous abuser de nos outils.


2. L'indentation à deux espaces pour les éléments imbriqués est-elle une pratique courante ?
    - Pour la lisibilité, il est important que nous utilisions l'indentation pour illustrer l'emboîtement, mais il n'existe pas de norme officielle sur le nombre d'espaces ou de tabulations à utiliser. Cela étant dit, l'indentation à deux espaces est courante et respecte [le guide de style HTML de Google](https://google.github.io/styleguide/htmlcssguide.html#Indentation).

___
| [Précédent](./5-headings.md)       | [Suivant](./7-attributs.md)        |


