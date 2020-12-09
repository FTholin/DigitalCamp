# flex-grow

Si le conteneur parent est plus grand que nécessaire, les éléments flexibles ne s'étireront pas par défaut.  
La propriété `flex-grow` nous permet de spécifier si les articles doivent s'étirer pour remplir un conteneur et également quels articles doivent s'étirer proportionnellement plus ou moins que les autres.

```html
<div class="container">
  <div class="side">
    <h1>Je suis sur le côté du conteneur souple !</h1>
  </div>
  <div class="center">
    <h1>Je suis au centre du conteneur souple !</h1>
  </div>
  <div class="side">
    <h1>Je suis de l'autre côté du conteneur souple !</h1>
  </div>
</div>
```

```css
.container {
  display: flex;
}

.side {
  width: 100px;
  flex-grow: 1;
}

.center {
  width: 100px;
  flex-grow: 2;
}
```

Dans l'exemple ci-dessus, `.container` a la règle `display: flex;`, ses trois divs enfants seront donc placés les uns à côté des autres.
S'il y a de l'espace supplémentaire dans le div .container (dans ce cas, s'il est plus large que 300 pixels), les éléments flexibles se développeront pour le remplir.

La div `center` s'entendra 2 fois plus que les div `.side`.  
Par exemple, s'il y avait 60 pixels d'espace supplémentaire, le div `center` absorberait 30 pixels et les divs `side` 15 pixels chacun.

Si `max-width` est fixée pour un élément, il ne sera pas plus grand que cela même s'il y a plus d'espace à absorber.

Toutes les propriétés précédentes que nous avons apprises sont déclarées sur les conteneurs flexibles, ou les éléments parents. 
Cette propriété `flex-grow` est la première que nous avons apprise qui est déclarée sur les éléments flexibles.


## A vous de jouer !

1. Reprendre le code [suivant](./versions-exercices/v0-13-6/)

2. Assignez aux classes `.top.side` et `.top.center` la règle `flex-grow: 1;`.
    - Étirez et rétrécissez le navigateur pour voir ce qui se passe.
  
3. Attribuez à `.middle.center` la règle `flex-grow: 1;`.
    - Étirez et rétrécissez à nouveau le navigateur.

4. Attribuez à `.bottom.side` la règle `flex-grow: 1;` et à `.bottom.center` la règle `flex-grow: 2;`. 
    - Réduisez et étirez à nouveau le navigateur. Comparez les différences de comportement des trois sections.
  
  
___
| [Précédent](./5-align-items.md)       | [Suivant](./7-flex-shrink.md)    |
