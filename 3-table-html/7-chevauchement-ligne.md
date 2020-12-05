# Chevauchement de Lignes

Les données peuvent également s'étendre sur plusieurs lignes grâce à l'attribut `rowspan`.

L'attribut `rowspan` est utilisé pour les données qui s'étendent sur plusieurs lignes (un événement peut se dérouler pendant plusieurs heures un jour donné). Il accepte un nombre entier (supérieur ou égal à 1) pour indiquer le nombre de lignes qu'il couvre.

```html
<table>
  <tr> <!-- Row 1 -->
    <th></th>
    <th>Samedi</th>
    <th>Dimanche</th>
  </tr>
  <tr> <!-- Row 2 -->
    <th>Matin</th>
    <td rowspan="2">Travail</td>
    <td rowspan="3">Détente</td>
  </tr>
  <tr> <!-- Row 3 -->
    <th>Midi</th>
  </tr>
  <tr> <!-- Row 4 -->
    <th>Soir</th>
    <td>Diner</td>
  </tr>
</table>
```
Voici le résultat du code :
<table>
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
</table>

___
Dans l'exemple ci-dessus, il y a quatre lignes :

1. La première ligne contient une cellule vide et les deux intitulés de colonne.

2. La deuxième rangée contient l'intitulé de la ligne Matin, ainsi que celui de la ligne Travail, qui s'étend sur deux rangées sous la colonne Samedi. L'entrée "Détente" s'étend sur trois lignes sous la colonne Dimanche.

3. La troisième ligne ne contient que l'en-tête de la ligne "Après-midi".

4. La quatrième rangée ne contient que l'entrée Dîner, puisque "Détente" s'étend dans la cellule voisine.

Si vous souhaitez voir comment le navigateur interprète le code ci-dessus, n'hésitez pas à le copier et le coller dans votre éditeur et le modifier pour le comprendre mieux.
___

| [Précédent](./6-chevauchement-col.md)       | [Suivant](./8-body.md)        |
