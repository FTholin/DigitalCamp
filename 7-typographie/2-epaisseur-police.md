# Épaisseur de police

Vous avez probablement remarqué du texte en gras dans les sites web que vous visitez, en particulier dans les sites d'information ou les sites à forte densité de texte.
Il est courant de mettre en gras des titres ou des mots clés importants.
En CSS, nous pouvons mettre le texte en gras avec la propriété `font-weight`.

Si nous voulons mettre du texte en gras dans une page web, nous pouvons définir la propriété `font-weight` sur `bold`.

```css
p {
  font-weight: bold;
}
```

Si nous voulons nous assurer que le texte n'est pas en gras, nous pouvons régler l'épaisseur de la police sur la valeur `normal`.

```css
p {
  font-weight: normal;
}
```

Par défaut, l'épaisseur de la police de la plupart des éléments est réglée sur `normal`.
Certains éléments, comme les en-têtes, ont un style gras intégré. 
Une bonne approche consiste à vérifier si l'élément de texte a un style par défaut, et à utiliser la propriété d'épaisseur de la police en conséquence.


Il est également possible d'attribuer une valeur numérique à la propriété `font-weight` sur une échelle numérique allant de 100 à 900. Les valeurs valides sont des multiples de `100` à l'intérieur de cette fourchette, comme `200` ou `500`.

Lorsque l'on utilise les valeurs numériques, il existe un certain nombre d'épaisseur que l'on peut utiliser :

- `400` est l'épaisseur par défaut dans la plupart des textes.
- `700` signifie une épaisseur de police en gras.
- `300` signifie une épaisseur de police fine.


Voyons un exemple d'utilisation de ces valeurs numériques.

```css
header {
  font-weight: 800;
}

footer {
  font-weight: 200;
}

```

Ici, l'en-tête apparaîtrait en gras profond, tandis que le pied de page serait plutôt fin.

Il est important de noter que toutes les polices ne peuvent pas être affectées avec une épaisseur numérique. 
Vous pouvez consulter la police que vous utilisez pour savoir quelles valeurs d'épaisseur de police sont disponibles.



## A vous de jouer !

1. Reprendre votre code.

2. Dans la feuille de style css, mettez en gras l'épaisseur de la police du paragraphe dans la classe `banner`.

3. Dans la section de l'en-tête (`header`), définissez une épaisseur de `900`. Vous remarquerez que les éléments de la liste dans la navigation s'épaississent.

___

| [Précédent](./1-police-caracteres.md)       |  [Suivant](./3-style-police.md)     |
