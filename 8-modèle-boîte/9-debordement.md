# Débordement

Tous les composants du modèle de boîte comprennent la taille d'un élément. Par exemple, une image qui a les dimensions suivantes a une largeur de 364 pixels et une hauteur de 244 pixels.

- *300 pixels* de large
- *200 pixels* de haut
- *10 pixels* de `padding` à gauche et à droite
- *10 pixels* de `padding` en haut et en bas
- Bordure de *2 pixels* à gauche et à droite
- Bordure de *2 pixels* en haut et en bas
- Marge de *20 pixels* à gauche et à droite
- Marge de *10 pixels* en haut et en bas

Les dimensions totales (`364px` par `244px`) sont calculées en additionnant toutes les dimensions verticales et toutes les dimensions horizontales. 
Parfois, ces composantes donnent un élément qui est plus grand que la surface de confinement du parent.

Comment pouvons-nous nous assurer que nous pouvons visualiser l'ensemble d'un élément qui est plus grand que la zone de confinement de son parent ?

La propriété `overflow` contrôle ce qui arrive au contenu qui se déverse, ou déborde, en dehors de sa boîte. Elle peut être réglée sur l'une des valeurs suivantes :

- `hidden` 
    - lorsqu'il est réglé sur cette valeur, tout contenu qui déborde sera caché de la vue.
- `scroll` 
    - si cette valeur est définie, une barre de défilement sera ajoutée à la boîte de l'élément afin que le reste du contenu puisse être visualisé par défilement.
- `visible` 
    - lorsque cette valeur est définie, le contenu en débordement sera affiché en dehors de l'élément contenant. Notez qu'il s'agit de la valeur par défaut.
___

```css
p {
  overflow: scroll; 
}
```

Dans l'exemple ci-dessus, si le contenu d'un paragraphe déborde (peut-être qu'un utilisateur redimensionne la fenêtre de son navigateur), une barre de défilement apparaîtra pour que les utilisateurs puissent voir le reste du contenu.

La propriété de débordement est définie sur un élément parent pour indiquer à un navigateur web comment rendre les éléments enfants. Par exemple, si la propriété de débordement d'une `div` est définie sur le défilement, tous les enfants de cette div afficheront le contenu débordant avec une barre de défilement.

## A vous de jouer !

1. Reprendre votre code.

2. Pour voir l'impact de la propriété `overflow: scroll`, modifiez d'abord la hauteur de l'élément `#main` à *1000 pixels* et faites défiler.

3. Définissez la propriété `overflow` de l'élément `#main` pour faire défiler.
     - Lorsque vous faites défiler vers le bas, une deuxième barre de défilement doit apparaître au-dessus de la section du paragraphe. Vous devrez peut-être développer le composant du navigateur afin de voir clairement ce comportement.
  
  
  
___
| [Précédent](./8-hauteur-min-max.md)       | [Suivant](./10-reinitialisation-default.md)       |
