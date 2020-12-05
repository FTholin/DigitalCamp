# Clear

La propriété `float` peut également être utilisée pour déplacer plusieurs éléments à la fois.
Cependant, lorsque plusieurs éléments se déplaçant ont des hauteurs différentes, cela peut affecter leur disposition sur la page. 
Plus précisément, les éléments peuvent se "heurter" les uns les autres et ne pas permettre à d'autres éléments de se déplacer correctement vers la gauche ou la droite.

La propriété `clear` précise comment les éléments doivent se comporter lorsqu'ils se croisent sur la page. Elle peut prendre l'une des valeurs suivantes :
1. `left`
  - le côté gauche de l'élément ne touchera aucun autre élément du même élément contenant.
  
2. `right`
  - le côté droit de l'élément ne touchera aucun autre élément du même élément contenant.
  
3. `both`
  - aucun côté de l'élément ne touchera un autre élément dans le même élément contenant.
  
4. `none`
  - l'élément peut toucher les deux côtés.

```css
div {
  width: 200px;
  float: left;
}

div.special {
  clear: left;
}
```

Dans l'exemple ci-dessus, tous les `<div>` de la page se déplace sur le côté gauche.
L'élément avec la classe `special` ne s'est pas déplacé complètement vers la gauche parce qu'un `<div>` plus grand a bloqué son positionnement.
En plaçant sa propriété "clear" à gauche, le `<div>` spécial sera déplacé jusqu'au côté gauche de la page.


## A vous de jouer !

1. Reprendre votre code.

2. Jetez un coup d'œil aux divs `.answer` sur la page web. Ils ont été déplacés vers la gauche, mais les divs `.question` touchent les divs .answer sur la droite, corrigeons cela.
    - Dans le sélecteur `.question`, mettez la propriété clear à `left`. Remarquez comment les questions se sont déplacées.
    
3. À bien y réfléchir, cette mise en page n'est pas très réussie. Enlevez la propriété `float` de `.answer` et la propriété `clear` de `.question`.

___
| [Précédent](./10-float.md)       | [Suivant (projet)](./pay-n-spray/explications.md)       |
