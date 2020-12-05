# Enchaînement et spécificité

Dans l'exercice précédent, au lieu de sélectionner tous les éléments `h5`, vous n'avez sélectionné que les éléments `h5` imbriqués dans les éléments `.description`.
Ce sélecteur CSS était plus spécifique que de n'écrire que `h5`. L'ajout de plusieurs balises, classes ou ID à un sélecteur CSS augmente la spécificité de ce dernier.

Par exemple, considérons le CSS suivant :
```css
p {
  color: blue;
}


.main p {
  color: red;
}
```

Ces deux règles CSS définissent ce à quoi doit ressembler un élément `p`. Comme le `.main p` possède une classe et une balise `p` comme sélecteur, seuls les `p` éléments à l'intérieur du `.main` element apparaîtront en rouge.
Cela se produit malgré une autre règle plus générale qui stipule que les `p` éléments doivent être bleus.

## A vous de jouer !

1. Reprendre votre code.

2. Dans le CSS, écrire un sélecteur pour les éléments `h5`. A l'intérieur des crochets, écrivez :
    ```css
    color: rebeccapurple;
    ```
    Remarquez que les éléments `h5` dans les descriptions ne changent pas de couleur. Ils continueront à être verts.
    Cela est dû au fait qu'il existe un sélecteur plus spécifique pour les éléments `h5` que vous avez écrit dans le dernier exercice.
    En raison du sélecteur CSS plus spécifique (`.description h5`), le sélecteur plus général de `h5` ne s'appliquera pas.

___

| [Précédent](./12-elements-imbriques.md)       | [Suivant](./14-selecteurs-multiples.md)        |
