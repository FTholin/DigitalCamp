# Position: Absolute

Une autre façon de modifier la position d'un élément est de fixer sa position à `absolute`.

Lorsque la position d'un élément est réglée sur `absolute`, tous les autres éléments de la page ignorent l'élément et agissent comme s'il n'était pas présent sur la page.
L'élément sera positionné par rapport à son élément parent le plus proche.

```css
.box-bottom {
  background-color: DeepSkyBlue;
  position: absolute;
  top: 20px;
  left: 50px;
}
```

Dans l'exemple ci-dessus, le `.box-bottom` sera déplacé vers le bas et vers la droite à partir du coin supérieur gauche de la vue.
Si les propriétés de décalage n'étaient pas spécifiées, la boîte supérieure serait entièrement couverte par la boîte inférieure.

## A vous de jouer !

1. Dans `style.css`, dans le sélecteur `header` fixer la propriété `position` à `absolute`.
    - Faites défiler la page web de haut en bas. Que remarquez-vous ?

2. Lorsque vous avez changé la propriété `position` à `absolute`, vous avez peut-être remarqué que l'en-tête (`header`) rétrécissait horizontalement.

3. Pour l'instant, fixez la propriété `width` de l'en-tête à 100%.

___
| [Précédent](./3-relative.md)       | [Suivant](./5-position-fixed.md)        |
