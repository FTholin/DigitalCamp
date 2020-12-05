# Entête de tableau
Dans le dernier exercice, les titres de la table ont été conservés à l'intérieur du corps de la table. Cependant, lorsque le corps d'un tableau est sectionné, il est également logique de sectionner les titres des colonnes du tableau à l'aide de l'élément `<thead>`.

```html
<table>
  <thead>
    <tr>
      <th></th>
      <th scope="col">Samedi</th>
      <th scope="col">Dimanche</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th scope="row">Matin</th>
      <td rowspan="2">Travail</td>
      <td rowspan="3">Relax</td>
    </tr>
    <tr>
     <th scope="row">Après-midi</th>
    </tr>
    <tr>
      <th scope="row">Soir</th>
      <td>Diner</td>
    </tr>
  </tbody>
</table>
```

Dans l'exemple ci-dessus, le seul élément nouveau est `<thead>`. Les titres des tableaux sont contenus à l'intérieur de cet élément. Notez que le titre du tableau nécessite toujours une ligne afin de contenir les titres du tableau.

De plus, seuls les titres de colonne passent sous l'élément `<thead>`.
Nous pouvons utiliser l'attribut scope sur les éléments `<th>` pour indiquer si un élément `<th>` est utilisé comme titre "row" ou "col".

## A vous de jouer !

1. Reprendre votre code duement complété.

2. Encadrez la première ligne du tableau dans un élément `<thead>`.
___

| [Précédent](./8-body.md)       |[Suivant](./10-pied-tableau.md)        |
