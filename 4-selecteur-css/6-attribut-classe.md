# Attribut de classe

Le CSS ne se limite pas à la sélection d'éléments par nom de balise. Les éléments HTML peuvent avoir plus qu'un nom de balise, ils peuvent aussi avoir des attributs. Un attribut commun est l'attribut de classe. Il est également possible de sélectionner un élément par son attribut de classe.

Prenons par exemple le HTML suivant :

```html
<p class="brand">La virgule</p>
```

L'élément paragraphe dans l'exemple ci-dessus a un attribut de classe dans la balise `<p>`. L'attribut de classe est défini sur `"brand"`. Pour sélectionner cet élément à l'aide du CSS, nous pourrions utiliser le sélecteur CSS suivant :

```css
.brand {

}
```

Pour sélectionner un élément HTML par sa classe en utilisant le CSS, un point (`.`) doit être ajouté au nom de la classe. Dans l'exemple ci-dessus, la classe est `brand`, donc le sélecteur CSS pour elle est `.brand`.

## A vous de jouer !

1. Reprendre votre code.

2. Dans le fichier CSS, ajouter un sélecteur CSS pour l'élément HTML de classe `title`.

3. A l'intérieur des accolades du sélecteur `.title` que vous venez de déclarer, écrivez :  
  `color: teal;`  

    Ce code changera la couleur du titre en vert, puisque l'élément titre `h1` a une classe  `title` dans le HTML. Vous pouvez voir l'élément HTML à la ligne `11`.

___

| [Précédent](./5-balise-name.md)       | [Suivant](./7-classes-multiples.md)       |
