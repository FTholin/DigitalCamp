# Pied de tableau

La partie inférieure d'un long tableau peut également être découpée à l'aide de l'élément `<tfoot>`.

```html
<table>
  <thead>
    <tr>
      <th>Trimestre</th>
      <th>Revenus</th>
      <th>Coûts</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>Q1</th>
      <td>10M€</td>
      <td>7.5M€</td>
    </tr>
    <tr>
      <th>Q2</th>
      <td>12M€</td>
      <td>5M€</td>
    </tr>
  </tbody>
  <tfoot>
    <tr>
      <th>Total</th>
      <td>22M€</td>
      <td>12.5M€</td>
    </tr>
  </tfoot>
</table>
```

Dans l'exemple ci-dessus, le pied de page contient les totaux des données du tableau. Les pieds de page sont souvent utilisés pour contenir des sommes, des différences et d'autres résultats de données.

## A vous de jouer !

1. Reprendre votre code duement complété.

2. Ajoutez un pied de table au bas du tableau en utilisant l'élément `<tfoot>`. À l'intérieur du pied de page, ajoutez les données suivantes :

```html
<td>Total</td>
<td>5</td>
```
___
| [Précédent](./9-entête.md)       | [Suivant (Projet)](./projet-nuit-fourrière/explications.md)        |
