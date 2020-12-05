# flex-shrink

Tout comme la propriété `flex-grow` étire proportionnellement les éléments flexibles, la propriété `flex-shrink` peut être utilisée pour spécifier quels éléments vont rétrécir et dans quelles proportions.

Vous avez peut-être remarqué, lors d'exercices précédents, que les éléments flexibles rétrécissaient lorsque le conteneur flexible était trop petit, même si nous n'avions pas déclaré la propriété.  
Ceci est du à la valeur par défaut de `flex-shrink` qui est égale à 1.
Cependant, les éléments flexibles ne s'alllongent  pas à moins que la propriété `flex-grow` soit déclarée, la valeur par défaut de `flex-grow` est `0`.

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
  flex-shrink: 1;
}

.center {
  width: 100px;
  flex-shrink: 2;
}
```


Dans l'exemple ci-dessus, la div `.center` se rétrécira deux fois plus que les divs `.side` si la div `.container` est trop petite pour y loger ses éléments.
Si le contenu de 60 pixels est trop grand pour celui qui l'entoure, le div `.center` se rétrécira de 30 pixels et les divs extérieurs se rétréciront de 15 pixels chacun. Les marges ne sont pas affectées par `flex-grow` and `flex-shrink`.

Gardez à l'esprit que les largeurs minimales et maximales auront la priorité sur `flex-grow` et `flex-shrink`.
Comme pour  `flex-grow`, `flex-shrink` ne sera utilisé que si le conteneur parent est trop petit ou si le navigateur est ajusté.

## A vous de jouer !

1. Reprendre le code [suivant](./versions-exercices/v0-13-7/).

2. Attribuez à `.top.side` la règle `flex-shrink: 2;`.
   - Étirez et rétrécissez le navigateur.
   - Comme la valeur par défaut de `flex-shrink` est `1`, la div `.top.center` se rétrécira, mais pas autant que les divs `.side`.
   
3. Attribuez à `.middle.side` une valeur de `0` pour `flex-shrink`.
   - Étirez et rétrécissez le navigateur. En quoi les divs `.middle` redimensionnent-ils différemment des divs `.top` ?

4. Attribuez à la division `.bottom.center` une valeur de `2` pour ` flex-shrink`.
   - Réduisez et étirez à nouveau le navigateur. En quoi la taille des divs `.bottom` est-elle différente de celle des divs `.top` et `.middle` ?

___
| [Précédent](./6-flex-grow.md)       | [Suivant](./8-flex-basis.md)    |
