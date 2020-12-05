# Marge

Jusqu'à présent, vous avez appris à connaître les éléments suivants du modèle de boîte : le *contenu*, les *bordures* et le *rembourrage*.
La quatrième et dernière composante du modèle de boîte est la *marge*.

La marge fait référence à l'espace situé directement à l'extérieur de la boîte. La propriété `margin` est utilisée pour spécifier la taille de cet espace.

```css
p {
  border: 1px solid aquamarine;
  margin: 20px;
}
```

Le code dans l'exemple ci-dessus placera *20 pixels* d'espace à l'extérieur de la case du paragraphe sur les quatre côtés.
Les éléments HTML de la page ne peuvent donc pas se trouver à moins de *20 pixels* de la bordure du paragraphe.

Si vous souhaitez être encore plus précis quant à la quantité de marge de chaque côté d'une case, vous pouvez utiliser les propriétés suivantes :

- `margin-top`
- `margin-right`
- `margin-bottom`
- `margin-left`

> Chaque propriété n'affecte la marge que d'un seul côté de la boîte, ce qui permet une plus grande souplesse de personnalisation.

```css
p {
  border: 3px solid DarkSlateGrey;
  margin-right: 15px;
}
```


Dans l'exemple ci-dessus, seul le côté droit de la case du paragraphe aura une marge de `15 pixels`. 
Il est courant de voir des valeurs de marge utilisées pour un côté spécifique d'un élément.

Et si vous ne voulez pas de marges égales sur les quatre côtés de la boîte ?

Une mise en œuvre similaire de la propriété de marge est utilisée pour spécifier exactement la marge qui doit être prévue de chaque côté de la case dans une seule déclaration.

```css
p {
  margin: 6px 10px 5px 12px;
}
```

Dans l'exemple ci-dessus, les quatre valeurs `6px 10px 5px 12px` se réfèrent à la marge autour de la boîte en rotation dans le sens des aiguilles d'une montre. Dans l'ordre, elle indique la quantité de marge sur les côtés **supérieur** (*6 pixels*), **droit** (*10 pixels*), **inférieur** (*5 pixels*) et **gauche** (*12 pixels*) de la boîte.

Lors de l'utilisation de cette implémentation de la propriété de marge, la valeur de la marge doit être spécifiée pour les quatre côtés de la boîte.

Tout comme le raccourci du `padding`, lorsque vous êtes certain que les valeurs supérieure et inférieure de `margin` seront égales l'une à l'autre, et que les valeurs **gauche et droite** de `margin` seront également égales l'une à l'autre, vous pouvez utiliser le raccourci suivant :

```css
p {
  margin: 6px 12px;
}
```

La première valeur, `6px`, fixe une valeur de marge pour le ***haut* et le *bas*** de la boîte. La deuxième valeur, `12px`, fixe une valeur de marge pour les côtés ***gauche* et *droit*** de la boîte.



## A vous de jouer !

1. Reprendre votre code.

2. Réglez la marge supérieure des éléments `<p>` à `60px`.

3. Regardez les trois cases rouges en bas de la page web. Ces éléments sont les éléments d'ancrage de la classe `.share`. Définissez les éléments de `.share a` de manière à ce qu'ils aient une marge de `10px`.

4. En utilisant deux valeurs, réglez les marges supérieure et inférieure de `<h2>` à *30 pixels* et les marges gauche et droite à *20 pixels*.



___

| [Précédent](./4-rembourrage.md)       |  [Suivant](./6-auto.md)       |
