# Titre

Les données des tableaux n'ont pas beaucoup de sens sans titres pour décrire ce que les données représentent.

Pour ajouter des titres aux lignes et aux colonnes, vous pouvez utiliser l'élément d'en-tête du tableau : `<th>`.

L'élément d'en-tête de tableau est utilisé comme un élément de données de tableau, sauf qu'il est accompagné d'un titre pertinent. Tout comme les données d'un tableau, un titre de tableau doit être placé dans une ligne (`<tr>`) du tableau.

```html
<table>
  <tr>
    <th></th>
    <th scope="col">Lundi</th>
    <th scope="col">Mardi</th>
  </tr>
  <tr>
    <th scope="row">Température</th>
    <td>73</td>
    <td>81</td>
  </tr>
</table>
```
Voici le résultat :
<table>
  <tr>
    <th></th>
    <th scope="col">Lundi</th>
    <th scope="col">Mardi</th>
  </tr>
  <tr>
    <th scope="row">Température</th>
    <td>15°C</td>
    <td>17°C</td>
  </tr>
</table>

___

Que s'est-il passé dans le code ci-dessus ?

Tout d'abord, une nouvelle ligne a été ajoutée pour contenir les trois titres : un titre vierge, un titre pour le Lundi et un titre pour le Mardi. L'intitulé vide crée la cellule supplémentaire nécessaire pour aligner correctement les intitulés du tableau sur les données auxquelles ils correspondent.

Dans la deuxième rangée, un titre de tableau a été ajouté comme titre de rangée : Température.

Notez également l'utilisation de l'attribut scope, qui peut prendre l'une des deux valeurs suivantes

1. `row`
    - cette valeur indique clairement que le titre est pour une ligne.
2. `col` 
    - cette valeur indique clairement que l'intitulé est une colonne.

Le code HTML des tableaux peut sembler un peu étrange au début, mais une analyse petit à petit permet de le rendre plus compréhensible.

## A vous de jouer !

1. Reprendre votre code duement complété.
2. Dans la première ligne, ajoutez trois titres de tableau. Les titres doivent contenir les champs suivants, dans l'ordre :
  - `N° VOL`
  - `HORAIRES`
  - `DESTINATIONS`

Ces rubriques ajouteront une signification au reste des données du tableau.

___

| [Précédent](./3-donnees.md)       | [Suivant](./5-bordure.md)        |
