# Projet Café CafPow!

Tout au long de ce projet, vous modifierez le code du site web du café CafPow afin que le site s'affiche correctement sur des écrans de tailles différentes. 
En outre, vous contribuerez à l'élaboration de styles qui rendront ce site plus attrayant.

1. Récupérer le code [suivant](./start/).


2. Le site web a besoin d'une image de fond dans pour sa section principale en haut de la page.
  - Ajoutez l'image suivante à la classe `.main` en tant qu'image de couverture `cover-sized `:
    - `https://nooksandnotions.files.wordpress.com/2015/09/image6.jpg`

```css
  background-image: url('...');
  background-repeat: no-repeat;
  background-position: center;
  background-size: cover;
  ```

3. Les éléments de navigation en haut de la page ont besoin de plus de `padding`.
  - Ajoutez un `padding` de `0.75rem` en haut et en bas, et de `1.25rem` à gauche et à droite des éléments de la liste de navigation.
> `padding: 0.75rem 1.25rem;`

4. L'image des grains de café sous la bannière principale dans la section de soutien est trop grande.
  - À l'intérieur du sélecteur de `.supporting img`, définissez les dimensions de hauteur et de largeur à 10 %.
  
 
5. L'image des grains de café est plus belle maintenant, mais le texte à droite doit être plus éloigné de l'image.
  - Réglez la marge droite de l'image à `5%`.
 > `margin-right: 5%;`  
 
6. La taille de  police doit être augmentée dans la section de notation.
  - Utilisez les unités `rem` pour que le texte `h1` soit équivalent à **40 pixels**. Cela peut être calculé sur la base de la taille de police de l'élément `html`.
> La taille de la police de l'élément html est de 16 pixels. Dans ce cas, `1rem` serait `16px`, `2rem` serait `32px` et `2.5rem` serait `40px`.

7. L'image de la carte en bas de page doit couvrir la largeur de la page, au lieu de déborder.
  - Ajoutez une largeur de `100%` à la règle CSS `.location img`.

8. Maintenant, la page est plus belle sur les grands écrans. Lorsque la page est redimensionnée à une largeur plus petite, la page doit être redimensionnée et réorganisée à l'aide de requêtes média.
  - Écrivez une requête de média qui cible l'écran lorsque sa largeur est inférieure à 960 pixels et moins.
```css
@media only screen and (max-width: 960px) {

}
```

9. Lorsque la page est redimensionnée à une largeur inférieure à 960 pixels, notez que la barre de navigation comporte un espace vide au-dessus d'elle. Dans la requête média que vous avez écrite à la dernière étape, 
    - Définir le remplissage supérieur de la classe `.main` sur `0`.


10. Redimensionnez le navigateur de grand à petit. Remarquez que l'image des grains de café dans la section de soutien fait que le paragraphe de soutien devient trop fin.
    - Écrivez une requête média pour les écrans de moins de 700 pixels.
    

11. A l'intérieur de la requête média, faites disparaître l'image en vous assurant que le sélecteur  `.supporting img` n'affiche rien.
    Vous pouvez faire disparaître un élément en utilisant la propriété et la valeur suivantes :
    `display: none;`
    
12. Continuez à redimensionner la largeur du navigateur jusqu'à ce que le site web ait la taille d'un petit écran.
    - Écrivez une requête média qui cible une largeur d'écran inférieure à 470 pixels.
    

13. Dans la requête média pour les petits écrans, vous devrez appliquer une variété de styles.
    - Tout d'abord, faites en sorte que la taille de la police h1 de la note soit équivalente à 32 pixels en utilisant les unités `rem`.

>La taille de la police du corps est de 16 pixels, ce qui équivaut à 1rem.

14. Les images de la galerie sont trop petites pour les petits écrans.
    - Sélectionnez les images dans la galerie et donnez-leur un style qui leur permette de remplir la largeur de l'écran.
    - Mettez leur marge à 0 pour qu'elles couvrent toute la page. 
    
> Cette règle doit être comprise dans la requête de média pour les écrans de moins de 470 pixels. Vous pouvez trouver le sélecteur pour les images de la galerie en regardant dans le CSS pour voir les styles actuels qui leur sont appliqués.

15. Le texte du pied de page n'est pas correctement formaté sur les petits écrans.
    - Cachez la navigation  (`nav`) à l'intérieur du pied de page (`footer`) pour mieux apparaître sur les petits écrans.
    - Redimensionnez l'écran de petit à grand et regardez votre site web changer son apparence pour s'adapter au mieux à la taille de l'écran. Vous venez de construire un site web réactif !
    
> Faire disparaître un élément :
  `display:none;`

___

| [Précédent](../16-point-arrêt.md)       | [Quiz Mesures relatives](https://moodle.ucly.fr/20-21/mod/quiz/view.php?id=32989)         | [Quiz Médias réactifs](https://moodle.ucly.fr/20-21/mod/quiz/view.php?id=32990)     |  [Suivant : 11-accessibilite](../../11-accessibilite/1-intro.md) |
