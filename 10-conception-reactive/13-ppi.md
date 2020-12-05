# Points par pouce ou Dots Per Inch (DPI)

Une autre caractéristique média que nous pouvons cibler est la résolution de l'écran.
Bien souvent, nous voudrons fournir du contenu visuel de meilleur qualité (images, vidéo, etc.) uniquement aux utilisateurs dont les écrans peuvent supporter ce contenu de haute résolution.
Le ciblage de la résolution de l'écran permet également aux utilisateurs d'éviter de télécharger des images en haute résolution (taille de fichier importante) que leur écran ne peut pas afficher correctement.

Pour cibler par résolution, nous pouvons utiliser `min-resolution` and `max-resolution`.

Ces supports acceptent une valeur de résolution en points par pouce (ppp) ou en points par centimètre (ppc). En savoir plus sur les [mesures de résolution](https://fr.wikipedia.org/wiki/Point_par_pouce)

```css
@media only screen and (min-resolution: 300dpi) {
    /* CSS for high resolution screens */
}
```

La requête média dans l'exemple ci-dessus cible les écrans haute résolution en s'assurant que la résolution de l'écran est d'au moins 300 points par pouce. Si la requête de résolution d'écran est satisfaite, nous pouvons alors utiliser le CSS pour afficher des images haute résolution ainsi que d'autres contenus.

## A vous de jouer !

1. Reprendre votre code.

2. Rédigez une requête média pour améliorer la qualité du logo si le visiteur regarde le site Amazing Space sur un écran haute résolution.
    - Un écran haute résolution peut avoir la propriété `min-resolution` à `150dpi`.
    
3. A l'intérieur de la requête média, ajoutez cette propriété CSS à la classe `.logo` :
```css
background-image: url("https://www.theblueeconomy.org/uploads/7/1/4/9/71490689/7949089.png");
```


___
| [Précédent](./12-plage.md)       | [Suivant](./14-operateur-and.md)        |
