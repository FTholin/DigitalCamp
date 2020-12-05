# Éléments imbriqués

En plus de l'enchaînement des sélecteurs pour sélectionner des éléments, le CSS prend également en charge la sélection d'éléments qui sont imbriqués dans d'autres éléments HTML. 
Par exemple, considérons le HTML suivant :

```html
<ul class='main-list'>
  <li> ... </li>
  <li> ... </li>
  <li> ... </li>
</ul>
```

Les éléments `<li>` imbriqués sont sélectionnés avec le CSS suivant :

```css
.main-list li {

}
```

Dans l'exemple ci-dessus, `.main-list` sélectionne l'élément `.main-list` (l'élément de liste non ordonné).
Les `<li>` imbriqués sont sélectionnés en ajoutant `li` au sélecteur, séparés par un espace, ce qui fait de `.main-list li` le sélecteur final.

En sélectionnant des éléments de cette manière, nous pouvons rendre nos sélecteurs encore plus spécifiques en nous assurant qu'ils apparaissent dans le contexte que nous attendons.

## A vous de jouer !

1. Reprendre votre code.

2. Dans le fichier HTMl, chaque destination a un paragraphe de description en dessous de lui. Dans chaque description, il y a une liste d'attraction.
Sélectionnons l'élément "*Lieux incontournables*" et faisons en sorte qu'il se distingue davantage en le rendant vert.
  Dans le CSS, ajouter un sélecteur qui cible tous les éléments `h5` imbriqués à l'intérieur des éléments avec la classe `.description`

3. A l'intérieur des parenthèses du sélecteur, écrivez :
    ```css
      color: teal;
    ```

___

| [Précédent](./11-enchainement-selecteurs.md)       | [Suivant](./13-enchainement-spécificité.md)        |
