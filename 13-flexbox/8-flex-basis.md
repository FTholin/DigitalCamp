# flex-basis

Dans les deux exercices précédents, les dimensions des divs étaient déterminées par des hauteurs et des largeurs fixées avec le CSS. Une autre façon de spécifier la largeur d'un élément flexible est avec la propriété `flex-basis`. Celle-ci nous permet de spécifier la largeur d'un article avant qu'il ne s'étire ou ne se rétrécisse.

```html
<div class="container">
  <div class=”side”>
    <h1>Côté gauche!</h1>
  </div>
  <div class="center">
    <h1>Centre!</h1>
  </div>
  <div class="side">
    <h1>Côté droit!</h1>
  </div>
</div>
```

```css
.container {
  display: flex;
}

.side {
  flex-grow: 1;
  flex-basis: 100px;
}

.center {
  flex-grow: 2;
  flex-basis: 150px;
}
```

Dans l'exemple ci-dessus, les divs `.side` auront une largeur de 100 pixels et la div `.center` aura une largeur de 150 pixels si la division `.container` a juste la bonne quantité d'espace (350 pixels, plus un petit extra pour les marges et les bordures). Si la div `.container` est plus grande, la div `.center` occupera deux fois plus d'espace que les div `.side`.

## A vous de jouer !

1. Reprendre le code [suivant](./versions-exercices/v0-13-8/).

2. Dans la règle `.grow.side` dans `style.css`, ajoutez la propriété `flex-basis` de `60px`.

3. Dans la même règle, ajoutez une valeur `flex-grow` de `1`.

4. Dans la règle `.grow.center` de `style.css`, ajoutez une valeur `flex-grow` de `3`.

5. Dans la règle `.shrink.side` dans `style.css`, ajoutez une valeur `flex-basis` de `300px`.

6. Dans la même règle, ajoutez une valeur `flex-shrink` de `3`.

7. Dans la règle `.shrink.center` dans `style.css`, ajoutez une valeur `flex-shrink` de `2`.

8. Dans la même règle, ajoutez `flex-basis` de `150px`. Maintenant, étirez et rétrécissez le navigateur pour voir ce qui se passe.


___
| [Précédent](./7-flex-shrink.md)       | [Suivant](./9-flex.md)    |
