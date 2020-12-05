# Opération Noctambule

1. Récupérer le code [suivant](./start) modifier seulement le fichier `index.html`

2. Dans `index.html`, à l'intérieur de l'élément `<div>` qui a la classe d'attribut avec une valeur de "container", créez un nouvel élément `<table>`.

3. À l'intérieur de l'élément `<table>`:
    - ajoutez une section pour les titres de tableaux en utilisant `<thead>`.
    - Ensuite, ajoutez deux lignes à l'intérieur de celui-ci en utilisant l'élément table row.

4. Dans le premier élément de la ligne de tableau, à partir de la tâche 3:
    - ajoutez un élément d'en-tête de tableau.
    - À l'intérieur de celui-ci, ajoutez un `<h1>` avec le texte suivant Programme de la fête du vin.

5. Dans le seconde ligne du tableau, à partir de la tâche 2, ajoutez deux `<th>` :
    - Dans le premier, ajoutez un `<h2>` qui indique `Date`.
    - Dans le second, ajoutez un `<h2>` qui indique `Évènement`.

6. Vous remarquerez peut-être que le "Programme de la fête" ne s'étend pas sur toute la table. Réglons ce problème !
    - Dans la balise `<th>` de l'ouverture de cet élément, ajoutez `colspan="2"`.

7. Sous la balise de fermeture `</thead>`, découper le code plus proprement avec un `<tbody>`.



7. À l'intérieur du corps du tableau que vous avez créé dans la tâche précédente, créez 5 lignes en utilisant l'élément `row` du tableau.

8. À l'intérieur de chaque ligne, créez deux cellules en utilisant l'élément de données du tableau.
   La première donnée du tableau de chaque ligne doit avoir la classe d'attribut avec la valeur `left`.


À ce stade, votre `<tbody>` devrait ressembler à :

```html
<tbody>
  <tr>
    <td class="left"> ... </td>
    <td> ... </td>
  </tr>
  <tr>
    <td class="left"> ... </td>
    <td> ... </td>
  </tr>
  <tr>
    <td class="left"> ... </td>
    <td> ... </td>
  </tr>
  <tr>
    <td class="left"> ... </td>
    <td> ... </td>
  </tr>
</tbody>
```

9. À l'intérieur de chacun des 5 éléments `<td class="left">`, ajoutez des éléments `<h3>` qui incluent les dates des événements :
      - 4 juin
      - 5 juin
      - 6 juin
      - 8 juin
    

10. Dans chacun des éléments `<td>` qui n'ont pas d'attribut de classe avec une valeur de `"left"`, ajoutez des éléments `<h3>` qui incluent le nom des événements:
      - MESSAGE IN A BOTTLE
      - Pomme
      - TINDERSTICKS BILL CALLAHAN
      - CARGO MALI-LYON
___

| [Précédent](../10-pied-tableau.md)       |      [Quiz](https://moodle.ucly.fr/20-21/mod/quiz/view.php?id=32982)     |  [Suivant : 4-selecteur-css](../../4-selecteur-css/1-style-en-ligne.md)  |
