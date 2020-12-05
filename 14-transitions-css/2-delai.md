# Délai

Notre prochaine propriété est `transition-delay`. Tout comme la durée, sa valeur est une quantité de temps. Le délai spécifie le temps d'attente avant de commencer la transition. Comme pour la propriété de la durée, la valeur par défaut du délai de transition est `0s`, ce qui signifie aucun délai.

```css
{
  transition-property: width;
  transition-duration: 750ms;
  transition-delay: 250ms;
}
```

Dans l'exemple ci-dessus, une modification de la largeur de l'élément commencera après un quart de seconde, et il s'animera pendant trois quarts de seconde.

## A vous de jouer !

1. Reprenez le code [suivant](./exercices-versions/v0-14-2/)

  
2. Réduire le délai en changeant la valeur à cent millisecondes.
    > css .game .gazelle { transition-delay : 3s ; }

    Exécutez le code et déplacez à nouveau votre souris sur Charlie. Cette fois, c'est rapide ! Un utilisateur pourrait gagner ce jeu en déplaçant sa souris au hasard sur l'image.

    > le délai de transition : 0.1s ;

3. Essayons une durée différente entre les deux dernières pour le délai, 0,75s. Qu'est-ce que cela donne ?

> le délai de transition : 0.75s ;

___
| [Précédent](./1-durée.md)       | [Suivant](./3-chronometrage.md)  |
