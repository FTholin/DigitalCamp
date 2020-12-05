# Plage ou Range

Des tailles d'écran spécifiques peuvent être ciblées en définissant plusieurs caractéristiques médias de largeur et de hauteur différentes. 

`min-width` et `min-heights`ont utilisées pour fixer respectivement la largeur minimale et la hauteur minimale.

À l'inverse, `max-width` et `max-height` définissent respectivement la largeur maximale et la hauteur maximale.  
En utilisant plusieurs largeurs et hauteurs, une plage peut être définie pour une requête média.

```css
@media only screen and (min-width: 320px) and (max-width: 480px) {
    /* ruleset for 320px - 480px */
}
```

L'exemple ci-dessus n'appliquerait ses règles CSS que lorsque la taille de l'écran est comprise entre 320 et 480 pixels

Remarquez l'utilisation du second mot clé `and` après la caractéristique média `min-width`. Cela nous permet d'enchaîner deux exigences.

L'exemple ci-dessus peut également être rédigé en utilisant deux règles distinctes :

```css
@media only screen and (min-width: 320px) { 
    /* ruleset for >= 320px */
}


@media only screen and (min-width: 480px) { 
    /* ruleset for >= 480px */
}
```

La première caractéristique média dans l'exemple ci-dessus appliquera les règles CSS lorsque la taille de l'écran atteint ou dépasse 320 pixels. La deuxième caractéristique de média appliquera ensuite des règles CSS lorsque la taille de l'écran atteint ou dépasse 480 pixels, ce qui signifie qu'elle peut remplacer les règles CSS présentes dans la première requête de média ou appliquer des règles CSS supplémentaires qui ne sont pas déjà présentes dans la première.

Les deux exemples ci-dessus sont valables, et il est probable que vous verrez les deux modèles utilisés lorsque vous lirez le code d'un autre développeur.

## A vous de jouer !

1. Reprendre votre code.

2. Faisons en sorte que les images de la galerie apparaissent plus grandes lorsque la taille de l'écran est petite à moyenne.
    - Écrivez une requête `@media` pour les tailles d'écran comprises entre `320px` et `480px`.
    - Utilisez la largeur minimale (`min-width`) et la largeur maximale (`max-width`) pour définir la plage.

3. Dans la requête média, sélectionnez les vignettes dans la galerie avec `.gallery-item .thumbnail` et donnez-leur une largeur de `95%`.
    - Vous devez noter que les images de la galerie apparaissent plus larges lorsque la taille de l'écran est comprise entre 320 et 480 pixels.

___
| [Précédent](./11-requetes-medias.md)       | [Suivant](./13-ppi.md)        |
