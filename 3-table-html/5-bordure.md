# Bordure de table

Jusqu'à présent, les tableaux que vous avez créés sont un peu difficiles à lire car ils n'ont pas de bordures.

Dans les anciennes versions du HTML, une bordure pouvait être ajoutée à un tableau en utilisant l'attribut border et en le définissant comme un nombre entier. Ce nombre entier représenterait l'épaisseur de la bordure.

```html
<table border="1">
  <tr>
    <td>73</td>
    <td>81</td>
  </tr>
</table>
```

Le code de l'exemple ci-dessus est déprécié, alors **ne l'utilisez pas**. Il est destiné à illustrer des conventions plus anciennes que vous pourriez rencontrer en lisant le code d'autres développeurs.

Le navigateur continuera probablement à interpréter correctement votre code si vous utilisez l'attribut border, mais cela ne signifie pas que cet attribut doit être utilisé.

Nous utilisons le CSS pour ajouter du style aux documents HTML, car il nous aide à séparer la structure d'une page de son apparence. Vous pouvez en apprendre davantage sur le CSS le cours sur le CSS. TODO lien interne

Vous pouvez obtenir un effet de bordure de tableau en utilisant le CSS suivant.

```css
table, td {
  border: 1px solid black;
}
```

Le code dans l'exemple ci-dessus utilise le CSS au lieu du HTML pour afficher les bordures des tableaux.

## A vous de jouer !

1. Reprendre votre code duement complété.

2. Nous allons avoir besoin de plus de données dans le tableau. Ajoutez les données suivantes dans le tableau. Veillez à les placer après la deuxième ligne du tableau.

```html
<tr>
  <td>OA670</td>
  <td>15:00-16:10</td>
  <td>Lyon-Amsterdam</td>
</tr>
<tr>
  <td>OA721</td>
  <td>17:00-18:00</td>
  <td>Lyon-Bordeaux</td>
</tr>
<tr>
  <td>OA684</td>
  <td>15:50-18:20</td>
  <td>Lyon-Lisbonne</td>
</tr>
<tr>
  <td>OA488</td>
  <td>16:00-18:50</td>
  <td>Lyon-Casablanca </td>
</tr>
```
___

| [Précédent](./4-titre.md)       | [Suivant](./6-chevauchement-col.md)        |
