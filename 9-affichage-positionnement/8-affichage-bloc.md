# Affichage des blocs

Certains éléments ne sont pas affichés dans la même ligne que le contenu qui les entoure. On les appelle des éléments de niveau bloc.
Ces éléments remplissent toute la largeur de la page par défaut, mais leur propriété de largeur (`width`) peut également être définie. 
Sauf indication contraire, ils ont la hauteur nécessaire pour accueillir leur contenu.

Les éléments qui sont de niveau bloc par défaut comprennent tous les niveaux d'éléments de titre (`<h1>` à `<h6>`), `<p>`, `<div>` et `<footer>`. Pour une liste complète des éléments de niveau bloc, consultez la [documentation MDN](https://developer.mozilla.org/en-US/docs/Web/HTML/Block-level_elements).

```css
strong {
  display: block;
}
```

Dans l'exemple ci-dessus, tous les éléments `<strong>` seront affichés sur leur propre ligne, sans contenu directement de chaque côté, même si leur contenu peut ne pas remplir la largeur de la plupart des écrans d'ordinateur.

## A vous de jouer !

1. Reprendre votre code.

2. Dans `index.html`, ajoutez un élément `<footer>` au bas du document, juste au-dessus de la balise de fermeture `body`.

3. Rien n'a changé ! C'est parce que l'élément `<footer>` est vide.
    - Ajoutez un élément `<h3>` dans le pied de page qui dit "Merci d'avoir répondu à notre sondage !".

4. Pour améliorer l'apparence de la page web, réglez la hauteur du pied de page à 100 pixels dans `style.css`.

___
| [Précédent](./7-affichage-en-ligne.md)       | [Suivant](./9-affichage-bloc-ligne.md)  |
