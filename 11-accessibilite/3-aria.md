# ARIA

Le texte d'une page web peut communiquer différents types d'informations.  
Certains textes peuvent constituer le contenu principal de la page, d'autres textes peuvent décrire des icônes de navigation, d'autres encore peuvent décrire des champs de saisie ou des menus.  
Il peut être difficile de placer un texte dans le contexte d'une page web sans savoir où il se trouve ni quel type d'information il est censé communiquer.

Pour aider à mettre en contexte les informations d'une page web, ARIA fournit un attribut HTML appelé `role`.  
La valeur du rôle d'un élément modifie la façon dont un lecteur d'écran communique l'élément.

```html
<div id="code-editor" role="complementary">
  ...
</div>
```

Pour plus de rôles visiter ce [lien](https://www.w3.org/TR/html-aria/#allowed-aria-roles-states-and-properties)

Certains éléments HTML, comme `<ul>` et `<ol>`, ne servent qu'à organiser l'information sur une page web.
Cependant, lorsqu'un lecteur d'écran navigue sur une page, il lit à l'utilisateur le nom de chaque élément au fur et à mesure qu'il les rencontre.
Par conséquent, lire "ol" à haute voix ralentira les utilisateurs malvoyants.

Nous pouvons demander aux lecteurs d'écran de ne pas lire les éléments inutiles en définissant l'attribut `role` à  `presentation`.

```html
<ol role="presentation">
  <li>List Item 1</li>
  <li>List Item 2</li>
</ol>
```

Dans l'exemple ci-dessus, l'élément `<ol>` se voit attribuer un rôle de présentation, ce qui signifie qu'un lecteur d'écran ne lira pas le nom de l'élément ("liste ordonnée").  
Ceci est acceptable, car un utilisateur n'a pas besoin d'entendre le nom de l'élément ("liste ordonnée") pour comprendre le contenu d'une liste.

Le rôle `presentation` passe outre les éléments et leurs enfants nécessaires.
Les éléments `<ol>` et `<ul>` nécessitent des enfants `<li>`. 
Par conséquent, l'ajout de `role="presentation"` à une balise `ol` fera que le lecteur d'écran passera directement au texte entre les balises `<li>` (il ne lira pas les noms des éléments `<li>`).

```html
<div id="container" role="presentation">
  <p>I'm content you want to hear!</p>
</div>
```

Dans l'exemple ci-dessus, un lecteur d'écran ne lira pas "div" à haute voix, mais il lira le nom de l'élément de paragraphe et le contenu du paragraphe. Cela se produit parce que le paragraphe n'est pas un enfant nécessaire de la div.


## A vous de jouer !

1. Reprendre votre code.

2. Ajoutez `role="note"` au `<span>` avec le texte Ada Lovelace est la programmeuse préférée de l'auteur de cette page web .

3. Ajoutez `role="presentation"` aux éléments `ul` dans le `nav` et le `footer` de `index.html`.

4. Ajouter `role="presentation"` à toutes les divs `.timeline`. 

___
| [Précédent](./2-elements-semantiques.md)       | [Suivant](./4-proprietes-aria.md)    |
