# Enchaînement des sélecteurs

Lors de la rédaction des règles CSS, il est possible d'exiger qu'un élément HTML ait deux ou plusieurs sélecteurs CSS en même temps.

Cela se fait en combinant plusieurs sélecteurs, ce que nous appellerons le chaînage.
Par exemple, s'il y avait une classe `.special` pour les éléments `h1`, le CSS ressemblerait :

```css
h1.special {

}
```

Le code ci-dessus ne sélectionnerait que les éléments `h1` qui ont une classe `special`.  
Si un élément `p` avait également une classe `special`, la règle dans l'exemple n'aurait pas le même style que le paragraphe.

## A vous de jouer !

1. Reprenez votre code.

2. Utilisons le chaînage pour sélectionner les destinations afin de leur donner un style.
   - Dans le CSS, écrivez un sélecteur CSS pour les éléments `h2` avec une classe  `.destination`.
   - Dans les accolades du sélecteur, écrivez ceci :
 
      ```css
      font-family: cursive;
      ```
      Cela rend les destinations cursives, comme le titre de l'article.

___

| [Précédent](./10-specificite.md)       | [Suivant](./12-elements-imbriques.md)        |
