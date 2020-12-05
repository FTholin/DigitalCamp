# Page web Savon artisanal

1. Récupérer le code [suivant](./start/index.html)

2. Avant de commencer, jetez un coup d'œil à la structure du site dans le HTML.
    - Commencez par réduire un peu l'image en haut de la page. Dans le fichier CSS, écrivez un sélecteur CSS pour la balise `img`.
    - A l'intérieur de ses accolades, écrivez :
    `height: 200px;`
    
 
3. La taille de police de la description de la recette doit être plus grande. Dans le CSS, écrivez un sélecteur CSS pour la classe `.description`.
    - À l'intérieur de ses accolades, ajoutez le CSS suivant :
    `font-size: 20px;`


    
4. Donnez du style aux temps de préparation. L'élément de la ligne 15 du fichier HTML possède un attribut id `preparation-time`.
    - Dans le CSS, ajoutez un sélecteur pour  l'id `preparation-time`.
    - A l'intérieur des paranthèses écrivez: 
     ```css
      font-weight: bold;
     ```
     
5. Changeons les puces de la liste des ingrédients en carrés au lieu de cercles ainsi que leurs couleurs.
   - Écrire un sélecteur pour les éléments `li` à l'intérieur de l'élément `.ingredients`.
   - À l'intérieur des parenthèses écrivez:
     `list-style: square;`
   - Modifier la couleur en ajoutant:
     `color: teal;`
     

6. Faisons apparaître en bleu le temps nécessaire à chaque étape de préparation.
   - Dans le CSS, écrivez un sélecteur pour `p` éléments qui ont également une classe de `.time`.
   - À l'intérieur des parenthèses écrivez: 
     `color: teal;`
     
  
7. En bas de la page, faisons en sorte que le lien ait une couleur différente.
   - Remarquez que dans le HTML, à la ligne 42, il y a un élément avec une classe `external-link`.
   - Ecrire un sélecteur pour cette classe.
   - Ajoutez ce code à l'intérieur des accolades du sélecteur :
     `color: SeaGreen;`
     
8. Changeons la police par défaut Times New Roman en `Helvetica`.
   - Au lieu d'écrire plusieurs sélecteurs pour appliquer la propriété `font-family`, écrivons un sélecteur qui applique un attribut `font-family` à tout le texte en même temps.
   - Le sélecteur doit cibler les éléments `h1`, `h2`, `p` et `li`.
   - Incluez cette ligne de code à l'intérieur des accolades :
     `font-family: Helvetica;`
     
  
9. Enfin rajoutons une règle pour personnaliser le titre principal la même couleur que les ingrédients avec une police `cursive`

___

| [Précédent](./1-introduction.md)       |   [Quiz](https://moodle.ucly.fr/20-21/mod/quiz/view.php?id=32983)     |   [Suivant : 5-regle-visuelle](../../5-regle-visuelle/1-structure-css.md)   |
