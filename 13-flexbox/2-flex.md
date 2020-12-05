# Flex

Tout élément peut être un conteneur flexible. Les conteneurs flex sont des outils utiles pour créer des sites web qui répondent aux changements de taille d'écran. Les éléments enfants des conteneurs souples changent de taille et d'emplacement en fonction de la taille et de la position de leur conteneur parent.

Pour qu'un élément devienne un conteneur flexible, sa propriété d'affichage doit être définie sur `flex`.

```css
div.container {
  display: flex;
}
```

Dans l'exemple ci-dessus, toutes les divs avec le conteneur de classe sont des conteneurs flex. S'ils ont des enfants, les enfants sont des éléments flex. Un `<div>` avec la déclaration  `display: flex;`  restera au niveau du bloc - aucun autre élément n'apparaîtra sur la même ligne que lui.

Toutefois, il modifiera le comportement de ses éléments enfants. Les éléments enfants ne commenceront pas sur de nouvelles lignes.

## A vous de jouer !

1. Récupérer le code [suivant](./versions-exercices/v0-13-2/).

2. Changez la propriété `display` de la div avec l'id flex pour avoir la valeur `flex`. Comparez les deux divs dans le navigateur.

___
| [Précédent](./1-intro.md)       | [Suivant](./3-inline-flex.md)    |
