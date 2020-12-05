# Les elements sémantiques HTML

Le moyen le plus rapide d'améliorer l'accessibilité des lecteurs d'écran est d'utiliser les balises appropriées pour une tâche donnée.

Par exemple, les développeurs doivent intégrer une barre de navigation dans la balise d'entête (`<header>`).
Bien que la barre de navigation puisse être enveloppée dans un élément `div` avec une classe d'en-tête, la sémantique native d'une balise d'en-tête permet à une personne utilisant un lecteur d'écran de comprendre et de naviguer plus efficacement sur une page web.

```html
<div id="header">
  <!-- Header Elements -->
</div>
```

Dans l'exemple ci-dessus, le contenu de l'en-tête est enveloppé dans une balise div avec l'en-tête ID. Bien que ce soit du HTML valide, une personne utilisant un lecteur d'écran ne comprendra pas le but de la balise div et devra plutôt reconstituer la page web en lisant à haute voix les éléments enfants.

La sémantique native d'une balise décrit l'objectif de la balise. Par exemple, la balise d'en-tête est destinée à contenir des éléments d'introduction et de navigation tels qu'un logo, des liens ou une barre de recherche.

```html
<header>
  <!--Header Elements-->
</header>
```

Dans l'exemple ci-dessus, le HTML rendra exactement le même contenu que celui du premier exemple. Toutefois, cet exemple utilise l'élément sémantique correct (`<header>`), ce qui permet à une personne utilisant un lecteur d'écran d'identifier facilement l'objectif des éléments à l'intérieur de l'en-tête.

## A vous de jouer !

1. Reprendre le code [suivant](./versions-exercices/v0-11-2/)

2. L'en-tête de ce site web est enveloppé dans un `div` avec l'id `header`.
    - Dans `index.html`, supprimez ce `div` et entourez cette section avec les balises `<header>` d'ouverture et de fermeture à la place.
  
3. Le CSS ne fonctionne plus correctement car nous avons changé le nom de l'élément.
    - Dans `style.css`, changez le sélecteur `#header` en `header`.

4. La navigation de ce site web est enveloppée dans un `div` avec l'id `nav`.
    - Dans `index.html`, supprimez ce `div` et entourez plutôt cette section d'une balise `<nav>` qui s'ouvre et se ferme.
  
5. Une fois de plus, nous devrons mettre à jour la feuille de style CSS puisque nous avons modifié le HTML.
    - Dans `style.css`, changez les trois sélecteurs `#nav` en `nav`. 
  
6. Le pied de page de ce site est enveloppé dans un `div` avec l'id `footer`.
    - Dans `index.html`, supprimez ce `div` et entourez plutôt cette section d'une balise `<footer>`.

7. Mettons à jour la feuille de style CSS une fois de plus.
    - Dans `style.css`, changez les deux sélecteurs `#footer` en `footer`.
 
___
| [Précédent](./1-intro.md)       | [Suivant](./3-aria.md)   |
