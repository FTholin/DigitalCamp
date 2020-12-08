# Chevauchement de colonnes à titre informationel

Que faire si le tableau contient des données qui s'étendent sur plusieurs colonnes ?

Par exemple, un calendrier personnel peut contenir des événements qui s'étendent sur plusieurs heures, voire plusieurs jours.

Les données peuvent s'étendre sur plusieurs colonnes grâce à l'attribut colspan. Cet attribut accepte un nombre entier (supérieur ou égal à 1) pour indiquer le nombre de colonnes qu'il couvre.

```html
<table>
  <tr>
    <th>Lundi</th>
    <th>Mardi</th>
    <th>Mercredi</th>
  </tr>
  <tr>
    <td colspan="2">Je suis absent</td>
    <td>Je suis présent</td>
  </tr>
</table>
```
Voici le résultat du code :
<table>
  <tr>
    <th>Lundi</th>
    <th>Mardi</th>
    <th>Mercredi</th>
  </tr>
  <tr>
    <td colspan="2">Je suis absent ici</td>
    <td>Je suis présent là</td>
  </tr>
</table>

___
Dans l'exemple ci-dessus, les données `Absent` couvrent les rubriques des tableaux du lundi et du mardi en utilisant la valeur 2 (deux colonnes). Les données `Présent` apparaissent uniquement sous le titre Mercredi.

## A vous de jouer !

1. Reprendre votre code duement complété.

2. Dans `index.html`, recouvrez un élément `<td>` sur deux colonnes.

🆘 Si par la suite, le formatage ne semble pas très bon, n'hésitez pas à supprimer l'attribut et la valeur `colspan` de l'élément `<td>` auquel vous les avez ajoutés.
___

| [Précédent](./5-bordure.md)       | [Suivant](./7-chevauchement-ligne.md)       |
