# Affichage des blocs en ligne

La troisième valeur pour la propriété `display` est `inline-block`.
L'affichage des blocs en ligne combine les caractéristiques des éléments en ligne et des blocs.
Les éléments de bloc en ligne peuvent apparaître les uns à côté des autres et nous pouvons spécifier leurs dimensions à l'aide des propriétés de `width` et de `height`.
Les images sont le meilleur exemple d'éléments de blocs en ligne par défaut.

Par exemple, les `<div>` dans le CSS ci-dessous seront affichés sur la même ligne et avec les dimensions spécifiées :

```html
<div class="rectangle">
  <p>I’m a rectangle!</p>
</div>
<div class="rectangle">
  <p>So am I!</p>
</div>
<div class="rectangle">
  <p>Me three!</p>
</div>
```

```css
.rectangle {
  display: inline-block;
  width: 200px;
  height: 300px;
}
```

Dans l'exemple ci-dessus, il y a trois divs rectangulaires qui contiennent chacun un paragraphe de texte. 

Les `<div>` `.rectangles` apparaîtront tous en ligne (à condition qu'il y ait suffisamment d'espace de gauche à droite) avec une largeur de 200 pixels et une hauteur de 300 pixels, même si le texte à l'intérieur n'a pas besoin de 200 pixels par 300 pixels d'espace.

## A vous de jouer !

1. Reprendre votre code.

2. Corrigeons l'affichage des balises `<li>` dans le menu en haut de la page.
    - Fixons la propriété `display` des éléments `li` à `inline-block`.
    
3. Réglez la largeur des éléments `li` à 80 pixels.

4. Maintenant, nous pouvons réduire le décalage supérieur de la section "Bienvenue". Réglez-le à 50 pixels.

5. Définissez la propriété `display` des éléments `.answer` sur `inline-block`.

___
| [Précédent](./8-affichage-bloc.md)       | [Suivant](./10-float.md)        |
