# Hauteur et largeur minimales et maximales

Comme une page web peut être consultée sur des écrans de tailles différentes, le contenu de la page web peut souffrir de ces changements de taille.
Pour éviter ce problème, le CSS offre deux propriétés qui peuvent limiter l'étroitesse ou la largeur de la boîte d'un élément.

- **min-width**
  - cette propriété garantit une largeur minimale de la boîte d'un élément.
- **max-width**
  - cette propriété garantit une largeur maximale de la boîte d'un élément.

```css
p {
  min-width: 300px;
  max-width: 600px;
}
```

Dans l'exemple ci-dessus, la largeur de tous les paragraphes ne sera pas réduite en dessous de *300 pixels*, ni ne dépassera *600 pixels*.

Le contenu, comme le texte, peut devenir difficile à lire lorsqu'une fenêtre de navigateur est réduite ou agrandie. Ces deux propriétés garantissent la lisibilité du contenu en limitant les largeurs minimale et maximale d'un élément.

Vous pouvez également limiter la hauteur minimale et maximale d'un élément.

- `min-height`
    — cette propriété garantit une hauteur minimale pour la boîte d'un élément.
- `max-height`
    — cette propriété garantit une hauteur maximale de la boîte d'un élément.
    
```css
p {
  min-height: 150px;
  max-height: 300px;
}
```


Dans l'exemple ci-dessus, la hauteur de tous les paragraphes ne sera pas réduite en dessous de *150 pixels* et la hauteur ne dépassera pas *300 pixels*.

Qu'arrivera-t-il au contenu de la boîte d'un élément si la propriété de hauteur maximale est fixée trop bas ? Il est possible que le contenu se répande en dehors de la boîte, ce qui entraîne un contenu non lisible.


## A vous de jouer !

1. Reprendre votre code.

2. Dans `style.css`, fixez la largeur minimale du paragraphe à `200 pixels`.

3. Fixez la largeur maximale du paragraphe à `800 pixels`.

4. Fixez la hauteur minimale du paragraphe à `200 pixels`.

5. Fixez la hauteur maximale du paragraphe à `300 pixels`.

> Une fois que vous avez réussi, redimensionnez le navigateur et remarquez la stabilité de vos paramétrages Vous devriez voir votre texte déborder. Dans le prochain exercice, nous allons corriger cela !

___


| [Précédent](./7-effondrement-marge.md)       | [Suivant](./9-debordement.md)       |
