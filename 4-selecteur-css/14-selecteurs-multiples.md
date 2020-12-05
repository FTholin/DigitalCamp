# Sélecteurs multiples

Afin de rendre le CSS plus concis, il est possible d'ajouter des styles CSS à plusieurs sélecteurs CSS en même temps.
Cela permet d'éviter d'écrire du code répétitif.

Par exemple, le code suivant possède des attributs de style répétitifs :

```css
h1 {
  font-family: Georgia;
}

.menu {
  font-family: Georgia;
}
```

Au lieu d'écrire la police de caractères  `font-family: Georgia` deux fois pour deux sélecteurs, on peut séparer les sélecteurs par une virgule pour appliquer le même style aux deux, comme ceci :

```css
h1, 
.menu {
  font-family: Georgia;
}
```

En séparant les sélecteurs CSS par une virgule, les éléments `h1` et `.menu` recevront tous deux la police de style `font-family: Georgia`.

## A vous de jouer !

1. Reprendre votre code.

2. Écrivez des sélecteurs pour les éléments `h5` et `p` de manière à ce qu'ils soient tous les deux coiffés avec la même règle CSS.  
   Appliquez ce style aux deux éléments :  
   
    `font-family: Georgia;`  

    Notez que la police de la page sera modifiée en `Georgia` sans avoir à écrire deux fois la même règle CSS.
Cela permet d'éviter d'écrire du code répétitif.

___

| [Précédent](./13-enchainement-spécificité.md)       | [Suivant (Projet)](./savon/explications.md)        |
