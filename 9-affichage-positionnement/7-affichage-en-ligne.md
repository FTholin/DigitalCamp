# Affichage en ligne

Chaque élément HTML a une valeur d'affichage par défaut qui dicte s'il peut partager l'espace horizontal avec d'autres éléments.
Certains éléments remplissent l'ensemble du navigateur de gauche à droite, quelle que soit la taille de leur contenu.
D'autres éléments n'occupent que l'espace horizontal nécessaire à leur contenu et peuvent se trouver directement à côté d'autres éléments.

Dans cette leçon, nous aborderons trois valeurs pour la propriété d'affichage :
  - `inline`
  - `block`
  - `inline-block`
  
L'affichage par défaut de certaines balises, telles que `<em>`, `<strong>` et `<a>`, est appelé *inline* (🇫🇷 : en ligne). 

Les éléments en ligne ont une boîte qui enveloppe étroitement leur contenu, ne prenant que l'espace nécessaire pour afficher leur contenu et ne nécessitant pas de nouvelle ligne après chaque élément. La hauteur et la largeur de ces éléments ne peuvent pas être spécifiées dans le document CSS.
Par exemple, le texte d'une balise d'ancrage (`<a>`) sera, par défaut, affiché sur la même ligne que le texte qui l'entoure, et il ne sera que d'une largeur nécessaire pour contenir son contenu.

Les éléments en ligne ne peuvent pas être modifiés en taille avec les propriétés CSS de hauteur ou de largeur.

```html
Pour en apprendre d'avantage sur les éléments <em>inline</em> , lire <a href="#">la documentation MDN</a>.   
```

Dans l'exemple ci-dessus, l'élément `<em>` est en ligne, car il affiche son contenu sur la même ligne que le contenu qui l'entoure, y compris la balise d'ancrage.
Cet exemple s'affichera :

La propriété d'affichage `display` en CSS offre la possibilité de faire de tout élément un élément en ligne.
Cela inclut les éléments qui ne sont pas en ligne par défaut, tels que les paragraphes, les divs et les titres.

```css
h1 {
  display: inline;
}
```

Le CSS dans l'exemple ci-dessus va changer l'affichage de tous les éléments `<h1>` en ligne.
Le navigateur affichera les éléments `<h1>` sur la même ligne que les autres éléments en ligne immédiatement avant ou après eux (s'il y en a).


## A vous de jouer !

1. Reprendre votre code.

2. Dans `index.html`, ajoutez les balises d'ouverture et de fermeture `<strong></strong>` autour de "Bienvenue". Remarquez que l'élément ne bouge pas. C'est parce que les éléments `<strong>` sont en ligne, ils peuvent donc partager des lignes avec d'autres éléments.


___
| [Précédent](./6-zindex.md)       | [Suivant](./8-affichage-bloc.md)       |
