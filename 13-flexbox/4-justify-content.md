# justify-content

Dans les exercices précédents, lorsque nous avons changé la valeur d'affichage des conteneurs parents pour flex ou inline-flex, tous les éléments enfants (éléments flex) se sont déplacés vers le coin supérieur gauche du conteneur parent. C'est le comportement par défaut des conteneurs flex et de leurs enfants. Nous pouvons spécifier la façon dont les éléments flex s'étendent de gauche à droite, le long de l'axe principal.  
Pour positionner les éléments de gauche à droite, nous utilisons une propriété appelée `justify-content`.

```css
.container {
  display: flex;
  justify-content: flex-end;
}
```

Dans l'exemple ci-dessus, nous fixons la valeur de justify-content à  flex-end. Cela aura pour effet de déplacer tous les éléments flexibles vers le côté droit du conteneur flexible.

Il y a cinq valeurs pour la propriété "justify-content" :

1. `flex-start` 
    - tous les articles seront placés dans l'ordre en commençant par la gauche du conteneur principal, sans espace supplémentaire entre eux ou devant eux.

2. `flex-end`
    - tous les articles seront placés dans l'ordre, le dernier article commençant sur le côté droit du conteneur principal, sans espace supplémentaire entre eux ou après.
    
3. `center`
    - tous les articles seront placés dans l'ordre, au centre du conteneur principal, sans espace supplémentaire avant, entre ou après eux.
    
4. `space-around` 
    - les éléments seront positionnés avec un espace égal avant et après chaque élément, ce qui doublera l'espace entre les éléments.
    
5. `space-between` 
    - les éléments seront placés avec un espace égal entre eux, mais sans espace supplémentaire avant le premier ou après les derniers éléments.
    
Dans les définitions ci-dessus, "no extra space" signifie que les marges et les bordures seront respectées, mais qu'il n'y aura pas plus d'espace (que ce qui est spécifié dans la règle de style pour l'élément particulier) entre les éléments. La taille de chaque élément flex individuel n'est pas modifiée par cette propriété.

## A vous de jouer !

1. Reprendre le code [suivant](./versions-exercices/v0-13-4/)

2. Attribuez à la div ayant l'id `#flexstart` la propriété `justify-content: flex-start;`.
3. Attribuez à la div ayant l'id `#flexend` la propriété `justify-content: flex-end;`.
4. Attribuez à la div ayant l'id `#center` la propriété `justify-content: center;`.
5. Attribuez à la div ayant l'id `#spacearound` la propriété `justify-content: space-around;`.
    - Étirez et rétrécissez la fenêtre du navigateur pour comparer et contraster le comportement des éléments de chaque div.
6. Attribuez à la div ayant l'id `#spacebetween` la propriété `justify-content: space-between;`.




___
| [Précédent](./3-inline-flex.md)       | [Suivant](./5-align-items.md)    |
