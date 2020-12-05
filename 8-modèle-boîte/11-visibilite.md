# Visibilité

Les éléments peuvent être cachés à la vue grâce à la propriété `visibiliy`.

Cette propriété peut être définie à l'une des valeurs suivantes :
- `hidden` - cache un élément.
- `visible` - affiche un élément.

```html
<ul>
  <li>Explore</li>
  <li>Connect</li>
  <li class="future">Donate</li>
</ul>
```

```css
.future {
  visibility: hidden;
}
```

Dans l'exemple ci-dessus, l'élément de liste avec une classe `future`  sera caché de la vue dans le navigateur.

N'oubliez pas, cependant, que les utilisateurs peuvent toujours voir le contenu de l'élément de liste (par exemple : `Donate`) en consultant le code source dans leur navigateur. En outre, la page web ne masquera que le contenu de l'élément. Elle laissera toujours un espace vide à l'endroit où l'élément est censé s'afficher.

* *Note* : Quelle est la différence entre `display: none` et `visibility: hidden` ?

Un élément avec la propriété `display : none` sera complètement supprimé de la page web. Un élément avec la propriété `visible : hidden`, ne sera pas visible sur la page web, mais l'espace qui lui est réservé le sera.


## A vous de jouer !

1. Reprendre le code HTML/CSS de l'exercice précédent.

2. Consultez la liste des éléments dans `index.html`. Notez que l'élément de la liste `Donate` a une classe `donate` dans le css.
  - Dans style.css :
    - Ajouter un sélecteur de classe pour `donate`.
    - Régler `visibility` sur `hidden`.
    
    
___
| [Précédent](./10-reinitialisation-default.md)       | [Suivant](./12-changer-modèles-boîte.md) |
