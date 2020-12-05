# Corps de tableau

Au fil du temps, un tableau peut se développer pour contenir beaucoup de données et devenir très long. Lorsque cela se produit, le tableau peut être découpé en sections afin d'être plus facile à gérer.

Les longs tableaux peuvent être découpés en utilisant l'élément de corps du tableau : `<tbody>`.

L'élément `<tbody>` doit contenir toutes les données du tableau, à l'exception des titres du tableau (nous y reviendrons dans un exercice ultérieur).

```html
<table>
  <tbody>
    <tr>
      <th></th>
      <th>Samedi</th>
      <th>Dimanche</th>
    </tr>
    <tr>
      <th>Matin</th>
      <td rowspan="2">Travail</td>
      <td rowspan="3">Détente</td>
    </tr>
    <tr>
     <th>Midi</th>
    </tr>
    <tr>
      <th>Soir</th>
      <td>Diner</td>
    </tr>
  </tbody>
</table>
```

Dans l'exemple ci-dessus, toutes les données de la table sont contenues dans un élément du corps de la table. Notez cependant que les titres ont également été conservés dans le corps du tableau - nous changerons cela dans le prochain exercice.

## A vous de jouer !

1. Reprenez ce code et encadrez les lignes 2, 3, 4, 5 et 6 du tableau dans un élément `<tbody>`.
___

| [Précédent](./7-chevauchement-ligne.md)       | [Suivant](./9-entête.md)        |
