# Rayon de bordure

Vous avez peut-être remarqué que les bordures mettent en évidence la véritable forme de la boîte d'un élément : le carré.
Grâce au CSS, une bordure n'a pas besoin d'être carrée.

Vous pouvez modifier les coins de la  bordure d'un élément avec la propriété `border-radius`.

```css
div.container {
  border: 3px solid rgb(22, 77, 100);
  border-radius: 5px;
}
```

Le code dans l'exemple ci-dessus fixera les quatre coins de la bordure à un rayon de 5 pixels (c'est-à-dire la même courbure qu'aurait un cercle de rayon 5 pixels).

Vous pouvez créer une bordure qui soit un cercle parfait en fixant le rayon à une hauteur égale à celle de la boîte, ou à 100 %.

```css
div.container {
  height: 60px;
  width: 60px;
  border: 3px solid rgb(22, 77, 100);
  border-radius: 100%;
}
```

Le code dans l'exemple ci-dessus crée un `<div>` qui est un cercle parfait.

## A vous de jouer !

1. Reprendre le code HTML/CSS précédent.

2. Dans `style.css`, définissez `border-radius` de `#banner .content h1` à `15px`.

3. Essayez d'expérimenter avec d'autres valeurs de rayons-frontières et lancez votre code pour voir le résultat !

___

| [Précédent](./2-bordure.md)       | [Suivant](./4-rembourrage.md)        |
