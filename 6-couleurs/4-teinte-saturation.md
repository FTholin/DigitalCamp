# Teinte, saturation et légèreté

Le schéma de couleurs **RVB** (**R**ouge **V**ert **B**leu) est pratique car il est très proche de la façon dont les ordinateurs représentent les couleurs en interne.
Il existe un autre système tout aussi puissant en CSS, appelé schéma de couleurs `teinte-saturation-légèreté`, abrégé en `HSL`.

La syntaxe du `HSL` est similaire à la forme décimale du `RVB`, bien qu'elle en diffère de manière importante.
Le premier nombre représente le degré de la teinte, et peut être compris entre `0 et 360`.
Les deuxième et troisième chiffres sont des pourcentages représentant respectivement la saturation et la luminosité.
Voici un exemple :

```css
color: hsl(120, 60%, 70%);
```

- **Hue** est le premier chiffre. Il fait référence à un angle sur une roue des couleurs. Le rouge est à 0 degré, le vert à 120 degrés, le bleu à 240 degrés, puis on revient au rouge à 360 degrés.
Vous pouvez voir un exemple de roue des couleurs ci-dessous :

**Image Roue Hue**

![Roue hue](https://c7.alamy.com/compfr/bb4506/roue-de-couleur-montrant-l-evolution-de-la-teinte-et-de-la-saturation-percus-ensemble-ils-composent-la-valeur-de-chrominance-d-une-image-bb4506.jpg)

- La **saturation** fait référence à l'intensité ou à la pureté de la couleur. Si vous imaginez un segment de ligne tracé du centre de la roue des couleurs jusqu'au périmètre, la saturation est un point sur ce segment de ligne. Si vous faites tourner ce segment de ligne sous différents angles, vous verrez à quoi ressemble la saturation pour différentes teintes. La saturation augmente vers 100 % à mesure que le point se rapproche du bord (la couleur devient plus riche).
La saturation diminue vers 0 % lorsque le point se rapproche du centre (la couleur devient plus grise).

- La **luminosité** fait référence au degré de clarté ou d'obscurité de la couleur. La moitié, ou 50 %, est la clarté normale. Imaginez un gradateur coulissant sur un interrupteur qui s'allume à mi-chemin. En faisant glisser le gradateur vers le haut, vers 100 %, la couleur devient plus claire, plus proche du blanc. En faisant glisser le variateur vers le bas, vers 0 %, la couleur devient plus foncée, plus proche du noir.

- La **HSL** est pratique pour ajuster les couleurs. En RVB, le fait de rendre la couleur un peu plus sombre peut affecter les trois composantes de la couleur. En HSL, c'est aussi simple que de changer la valeur de la luminosité. La HSL est également utile pour créer un ensemble de couleurs qui fonctionnent bien ensemble en sélectionnant différentes couleurs qui ont la même luminosité et saturation mais des teintes différentes.

---
Outil : [Ici vous pouvez visualiser comment cette méthode fonctionne.](http://medialab.github.io/iwanthue/)

___

| [Précédent](./1-introduction.md)       |   [Quiz](https://moodle.ucly.fr/20-21/mod/quiz/view.php?id=32985)   |  [Suivant : 7-typographie](../7-typographie/1-police-caracteres.md)  |
