# Attributs
Nous pouvons *étendre* la balise d'un élément HTML en utilisant un attribut. Les attributs sont du contenu ajouté à la balise d'ouverture d'un élément et peuvent être utilisés de plusieurs façons différentes, de la fourniture d'informations à la modification du style. Les attributs sont composés des deux parties :
- Le **nom** de l'attribut
- La **valeur** de l'attribut

Un attribut couramment utilisé est l'id. Nous pouvons utiliser l'attribut id pour spécifier différents contenus (comme `<div>`) et il est vraiment utile lorsque vous utilisez un élément plusieurs fois. Les ids ont plusieurs objectifs différents en HTML, mais pour l'instant, nous allons nous concentrer sur la façon dont ils peuvent nous aider à identifier le contenu de notre page.

Lorsque nous ajoutons un identifiant à un `<div>`, nous le plaçons dans la balise d'ouverture :

```html
<div id="intro">
  <h1>Introduction</h1>
  <p> Beaucoup de blabla ... </p>
</div>
```
## A vous de jouer !

1. Reprendre votre code.

2. Ajoutez un attribut id avec la valeur "introduction" à la balise `<div>` qui se trouve sous l'en-tête `Spiruline` `<h1>`.

3. Ajoutez un attribut `id` avec la valeur "habitat" à la balise d'ouverture `<div>` qui a la rubrique `Habitat` `<h2>` comme un enfant.

4. Ajoutez un attribut `id` avec la valeur "image" à la balise d'ouverture `<div>` qui a l'en-tête `Image` `<h2>` comme un enfant.

## Réflexions
1. Dans cet exercice, nous donnons un identifiant aux multiples balises `<div>`. Toute balise `<html>` d'ouverture peut-elle avoir un attribut `id` ou seules les balises `<div>` d'ouverture peuvent-elles avoir cet attribut ?
   - Toute ouverture `<html>` tag peut avoir un attribut `id`. Alors que l'attribut id définit un identifiant qui doit être unique pour l'ensemble du document, il n'est pas rare que plusieurs balises `<html>` différentes aient des attributs `id` uniques. Pour savoir quels attributs sont disponibles pour chaque balise, consultez cette liste d'attributs globaux

2. Cet exercice indique que les attributs peuvent fournir des informations. Quel type d'information les attributs fournissent-ils ?
   - Il existe plusieurs types d'attributs qui peuvent étendre les balises de différentes manières. En général, les attributs modifient le comportement d'un élément, fournissent des métadonnées sur l'élément ou fournissent des informations d'étiquetage sur l'élément. Par exemple, l'attribut `id` identifie de manière unique un élément alors que l'attribut `class` identifie tout un groupe d'éléments. Ces informations d'étiquetage peuvent ensuite être utilisées pour cibler le contenu en vue d'un style, d'un script ou, pour l'attribut `id`, d'un lien.
___
| [Précédent](./6-div.md)       | [Suivant](./8-affichage-texte.md)       |
