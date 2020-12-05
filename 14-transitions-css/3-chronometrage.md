# Fonction de chronométrage

La dernière propriété de transition est `transition-timing-function`.

La fonction de chronométrage décrit le rythme de la transition.

La valeur par défaut est ease, qui démarre la transition lentement, accélère au milieu et ralentit à la fin.

Les autres valeurs valides sont les suivantes :

- `ease-in`
  - démarre lentement, accélère rapidement, s'arrête brusquement
- `ease-out`
  - commence brusquement, ralentit et se termine lentement
- `ease-in-out`
  - commence lentement, devient rapide au milieu et se termine lentement
- `linear`
  - vitesse constante tout au long
  
```css
{
  transition-property: color;
  transition-duration: 1s;
  transition-timing-function: ease-out;
}
```

Dans l'exemple ci-dessus, la couleur du texte sera animée pendant une seconde. La fonction de chronométrage a pour valeur `ease-out`, ce qui signifie qu'elle commence brusquement et ralentit à la fin.

Si vous souhaitez en savoir plus sur les fonctions de chronométrage ou voir la liste complète des valeurs possibles, nous vous recommandons cette [ressource](https://developer.mozilla.org/en-US/docs/Web/CSS/transition-timing-function) du Mozilla Developer Network.

## A vous de jouer !

1. Reprendre le code précédent.

2. Ajoutez `transition-timing-function` comme propriété à la `.game .charlie` avec la valeur `ease-out`.
    - Passez votre souris sur la gazelle pour observer la différence de mouvement. Si vous ne pouvez pas faire la différence, vous pouvez modifier la valeur de la durée de la transition pour qu'elle soit plus longue.

3. Maintenant, changez la valeur en `ease-in`. Observez à nouveau la différence.

4. Changez la valeur de la fonction de temporisation avec la valeur `linear`. Comment cela affecte-t-il la vitesse du mouvement ?

5. Changez la valeur en `ease-in-out`. Observez à nouveau la différence.

6. Remettez la valeur par défaut, `ease `. Pouvez-vous distinguer la différence mineure entre `ease-in-out` et `ease` ?

___
| [Précédent](./2-delai.md)       | [Suivant](./4-abreviation.md)    |
