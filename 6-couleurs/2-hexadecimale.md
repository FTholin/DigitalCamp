# Hexadécimal

Une syntaxe que nous pouvons utiliser pour spécifier les couleurs est appelée hexadécimale. Les couleurs spécifiées à l'aide de ce système sont appelées couleurs hexadécimales. Une couleur hexadécimale commence par un dièse (#) qui est suivi de trois ou six caractères.
Les caractères représentent les valeurs pour le rouge, le bleu et le vert.
___
| Color                                                    | Hexadecimal | Name         |
|----------------------------------------------------------|-------------|--------------|
| ![#8FBC8F](https://placehold.it/15/8FBC8F/000000?text=+) | #8FBC8F     | DarkSeaGreen |
| ![#A0522D](https://placehold.it/15/A0522D/000000?text=+) | #A0522D     | Sienna       |
| ![#8B4513](https://placehold.it/15/8B4513/000000?text=+) | #8B4513     | SaddleBrown  |
| ![#A52A2A](https://placehold.it/15/A52A2A/000000?text=+) | #A52A2A     | Brown        |
| ![#000000](https://placehold.it/15/000000/000000?text=+) | #000000 or #000    | Black        |
| ![#FFFFFF](https://placehold.it/15/FFFFFF/000000?text=+) | #FFFFFF or #FFF    | White        |
| ![#00FFFF](https://placehold.it/15/00FFFF/000000?text=+) | #00FFFF or #0FF    | Aqua         |  
___

Dans l'exemple ci-dessus, vous pouvez remarquer qu'il y a à la fois des lettres et des chiffres dans les valeurs.
Cela s'explique par le fait que le système des nombres hexadécimaux comporte `16 chiffres` (`0-15`) au lieu de `10` (`0-9`) comme vous en avez l'habitude.
Pour représenter `10-15`, nous utilisons `A-F`. Voici une liste de nombreuses couleurs différentes et de leurs valeurs hexadécimales.

Notez que le noir, le blanc et l'aqua sont tous représentés par trois et six caractères.
Cela peut être fait avec des couleurs dont les paires de chiffres sont les mêmes caractères. Dans l'exemple ci-dessus, `Aqua` peut être représenté par `#0FF` car les deux premiers caractères sont 0 et les deuxième et troisième paires de caractères sont toutes deux des F.
Gardez à l'esprit que les trois couleurs peuvent être représentées par six caractères (en répétant chaque caractère deux fois), mais qu'il n'en va pas de même à l'inverse.

Vous pouvez inclure des couleurs hexadécimales tout comme vous incluriez des couleurs nommées : 
```css
{
    background-color: #9932cc;
}
```

___

| [Précédent](./1-premier-plan-fond.md)       |[Suivant](./3-rgb.md)        |
