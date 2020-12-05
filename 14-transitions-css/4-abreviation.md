# Abréviation

Maintenant que nous avons exploré chaque propriété de transition, vous pouvez vous retrouver avec de nombreux ensembles de règles CSS qui ressemblent au code ci-dessous.
```css
{
  transition-property: color;
  transition-duration: 1.5s;
  transition-timing-function: linear;
  transition-delay: 0.5s;
}
```

Comme ces quatre propriétés sont si souvent déclarées ensemble, le CSS fournit une propriété qui peut être utilisée pour les déclarer toutes sur une seule ligne : `transition`. Cette propriété sténographique décrit chaque aspect du puzzle de la transition dans une déclaration unique.
Les propriétés doivent être spécifiées dans cet ordre :

- `transition-property`
- `transition-duration`
- `transition-timing-function`
- `transition-delay`.
___

```css
{
  transition: color 1.5s linear 0.5s;
}
```
Dans l'exemple ci-dessus, nous avons regroupé les quatre lignes de code de l'exemple précédent en une seule ligne concise.   
Dans cet exemple, tout changement de couleur du texte se fera à une vitesse constante pendant 1,5 seconde, après un délai de 0,5 seconde.

L'omission d'une des propriétés entraîne l'application de la valeur par défaut de cette propriété.  
Il y a une exception : Vous devez définir la durée si vous voulez définir un délai.  
Comme il s'agit dans les deux cas de valeurs de temps, le navigateur interprétera toujours la première valeur de temps qu'il voit comme une durée.

## A vous de jouer !

1. Reprendre le code précédent.

2. Combinez toutes les propriétés de transition de charlie en une seule règle abrégée. La propriété en transition doit être `max-height`. Utilisez une durée de 750 ms et un délai de 750 ms. La fonction de temporisation doit être `ease-in`.

___
| [Précédent](./3-chronometrage.md)       | [Suivant](./5-combinaisons.md)    |
