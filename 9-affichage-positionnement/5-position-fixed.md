# Position: Fixed

Lorsque la position d'un élément est réglée sur `absolute`, comme dans le dernier exercice, l'élément défilera avec le reste du document lorsqu'un utilisateur fait défiler.

Nous pouvons fixer un élément à une position spécifique sur la page (indépendamment du défilement de l'utilisateur) en fixant `position` à `fixed`.

```css
.box-bottom {
  background-color: DeepSkyBlue;
  position: fixed;
  top: 20px;
  left: 50px;
}
```

Dans l'exemple ci-dessus, le `.box-bottom` restera fixé à sa position quel que soit l'endroit où l'utilisateur fait défiler la page

## A vous de jouer !

1. Dans `style.css`, changez la position de la règle d'en-tête en `fixed`. Faites défiler la page web de haut en bas. Que remarquez-vous ?

2. Notez qu'une partie de la section "Bienvenue" est maintenant recouverte par l'en-tête. C'est parce que lorsque nous avons changé la position de l'en-tête en `fixed`, nous l'avons retiré du flux du document html.
    - Changez la position de l'élément `.welcome` en `relative`.

3. Décalez la section `welcome` de 200 pixels à partir du haut. Il se peut que tout ne s'affiche pas encore correctement ; nous y remédierons dans un exercice ultérieur.

___
| [Précédent](./4-absolute.md)       |  [Suivant](./6-zindex.md)
       |
