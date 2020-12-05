# Listes non ordonnées

En plus d'organiser le texte sous forme de paragraphes, vous pouvez également afficher le contenu dans une liste facile à lire.

En HTML, vous pouvez utiliser une balise de liste non ordonnée (`<ul>`) pour créer une liste d'éléments sans ordre particulier. Une liste non ordonnée présente les éléments individuels de la liste avec un point.

L'élément `<ul>` ne doit pas contenir de texte brut et ne formatera pas automatiquement le texte brut en une liste d'éléments non ordonnée. Les éléments individuels de la liste doivent être ajoutés à la liste non ordonnée à l'aide de la balise `<li>`. La balise `<li>` ou élément de liste est utilisée pour décrire un élément dans une liste.

```html
<ul>
  <li>Avoine</li>
  <li>Miel</li>
  <li>Spiruline</li>
</ul>
```

Dans l'exemple ci-dessus, la liste a été créée en utilisant la balise `<ul>` et tous les éléments individuels de la liste ont été ajoutés en utilisant les balises `<li>`.

La sortie ressemblera à ceci :

- Avoine
- Miel
- Spiruline

## A vous de jouer !

1. Reprendre votre code duement complété.

2. Sous la rubrique `Espèces`, créez une liste non ordonnée.
N'ajoutez aucun élément à la liste pour l'instant.

3. Ajoutez les éléments suivants à la liste non ordonnée :
  - Paracas
  - Camargue

## Réflexions
1. Que se passe-t-il si nous mettons du texte brut directement dans l'élément `<ul>` ?
    - Les navigateurs sont conçus pour être très indulgents et très tolérants aux erreurs, de sorte que dans ce cas, le texte s'afficherait sur la page. Cependant, il ne serait pas affiché sous forme de liste et ce n'est pas une bonne pratique car il défie la spécification HTML5.
    - Pour garantir que notre HTML respecte les normes, nous devrions le faire passer par un [validateur](https://validator.w3.org).

2. La balise `<li>` doit-elle toujours être imbriquée dans la balise `<ul>` ?
    - L'élément `<li>` peut être un enfant direct des éléments `<ul>` ou `<ol>`, mais il ne doit jamais exister en dehors de l'un de ces éléments parents.

3. Les éléments de la liste que nous avons créés sont en retrait par rapport au reste du texte de cette page. Y a-t-il un moyen de faire en sorte que les éléments de la liste soient alignés sur la page comme le reste du texte ?
    - En effet, il y a un moyen ! La plupart des navigateurs utilisent une feuille de style par défaut pour appliquer un certain rembourrage à gauche des éléments `<ul>` et `<ol>`. Les développeurs peuvent écraser ce remplissage par défaut en créant leurs propres feuilles de style CSS personnalisées.

___

| [Précédent](./10-saut-ligne.md)       | [Suivant](./12-liste-ordonnee.md)        |
