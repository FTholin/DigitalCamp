# Listes ordonnées
Les listes ordonnées (`<ol>`) sont comme les listes non ordonnées, sauf que chaque élément de la liste est numéroté. Elles sont utiles lorsque vous devez énumérer les différentes étapes d'un processus ou classer les éléments du premier au dernier.

Vous pouvez créer la liste ordonnée avec la balise `<ol>` et ensuite ajouter des éléments individuels à la liste en utilisant les balises `<li>`.

```html
<ol>
  <li>Préchauffez le four à 350 degrés.</li>
  <li>Mélangez la farine de blé complet, le bicarbonate de soude et le sel.</li>
  <li>Dans un bol séparé, crémer le beurre et le sucre.</li>
  <li>Ajoutez les oeufs et l'extrait de vanille dans le bol.</li>
</ol>
```

Le résultat ressemblera à ceci :

1. Préchauffez le four à 350 degrés.
2. Mélangez la farine de blé complet, le bicarbonate de soude et le sel.
3. Dans un bol séparé, crémer le beurre et le sucre.
4. Ajoutez les oeufs et l'extrait de vanille dans le bol.


##### A vous de jouer !

1. Reprendre votre code dument complété.

2. Sous la rubrique `Amérique`, ajoutez une liste ordonnée. N'ajoutez aucun élément à la liste pour l'instant.

3. Ajoutez les éléments suivants à la liste ordonnée :
  - Mexique
  - Pérou
  
4. Sous la rubrique "Afrique", ajoutez une liste ordonnée avec les éléments suivants:
  - Tchad
  - Côte d'Ivoire
  - Mali
  - Burkina Faso
  
## Réflexions
1. L'élément `<li>` peut-il contenir un contenu autre que du texte ? Par exemple, pouvons-nous avoir des listes de vidéos ou de chansons, des hyperliens ou une combinaison des trois ?
    - Oui, nous le pouvons ! L'élément `<li>` peut contenir n'importe quel élément valide dans la balise `<body>`. Cela signifie que nous pouvons avoir des listes de vidéos, d'images, de chansons, d'hyperliens ou toute combinaison de ces éléments. En fait, nous pouvons même avoir des listes de listes !

2. Peut-on seulement afficher des numéros ou des listes de points ?
    - Avec un peu de CSS, nous pouvons être plus créatifs avec nos styles de liste.

3. Y a-t-il un moyen d'augmenter l'espace entre le nombre et le texte de chaque `<li>` ?
    - Oui, il existe un moyen de le faire ! Nous pouvons utiliser le CSS pour cibler les éléments `<li>` et ensuite leur appliquer un peu de rembourrage à gauche. Cela poussera le texte vers la droite, à l'écart des chiffres. Pour en savoir plus sur la façon de changer l'apparence de nos pages, consultez le cours Apprendre le CSS.

___

| [Précédent](./11-liste-non-ordonnée.md)       | [Suivant](./13-image.md)        |
