# Bordure

Une bordure est une ligne qui entoure un élément, comme un cadre autour d'un tableau. Les frontières peuvent être définies avec un `width`, `style`, et `color`.

1. `width`
    - L'épaisseur d'une bordure peut être définie en pixels ou avec l'un des mots-clés suivants :
        - `thin`
        - `medium`
        - `thick`
        
2. `style`
    - La conception graphique de la bordure comprend certains styles :
        - `none`
        - `dotted`
        - `solid`
    > D'autres [styles disponibles](https://developer.mozilla.org/en-US/docs/Web/CSS/border-style#Values)
    
3. `color`
    - La couleur de la bordure. Les navigateurs web peuvent rendre les couleurs en utilisant quelques formats différents [140 mots-clés de couleur intégrés](https://developer.mozilla.org/en-US/docs/Web/CSS/color_value)
    
    ```css
    p {
      border: 3px solid coral;
    }
    ```
    
Dans l'exemple ci-dessus, la bordure a une largeur de `3 pixels`, un style `solid` et une couleur `coral`.
Ces trois propriétés sont définies dans une seule ligne de code.

La bordure par défaut est `medium none color`, où la couleur est la couleur actuelle de l'élément. Si la `largeur`, le `style` ou la `couleur` ne sont pas définis dans le fichier CSS, le navigateur web attribue la valeur par défaut à cette propriété.

```css
p.content-header {
  height: 80px;
  width: 240px;
  border: solid coral;
}
```

Dans cet exemple, le style de la bordure est réglé sur `solid` et la couleur est réglée sur `coral`. La largeur n'est pas définie, donc la valeur par défaut est `medium`.

## A vous de jouer !

1. Reprendre votre code.

2. Ajoutez une bordure rouge pointillée de `1px` à toutes les éléments `<h2>`.

3. Ajoutez une bordure à la règle `#banner .content h1`.
    - La largeur de la bordure est de 3 pixels.
    - couleur `white`
    - style `solid`
 
___

| [Précédent](./1-boîte-intro.md)       | [Suivant](./3-rayon-bordure.md)    |
