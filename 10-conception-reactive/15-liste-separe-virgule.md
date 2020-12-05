# Liste séparée par des virgules

Les caractéristiques médias peuvent être séparées dans une liste séparée par une virgule.

Par exemple, si nous devons appliquer un style alors qu'un seul des éléments ci-dessous est vrai :
 - L'écran a une largeur de plus de 480 pixels
 - L'écran est en mode paysage
 
Nous pourrions écrire :

```css
@media only screen and (min-width: 480px), (orientation: landscape) {
    /* CSS ruleset */
}
```

Dans l'exemple ci-dessus, nous avons utilisé une virgule (`,`) pour séparer plusieurs règles. Une seule des caractéristiques média doit être vraie pour que son CSS s'applique.

Notez que le seconde caractéristique média est l'`orientation`. La caractéristique d'orientation  détecte si la page a plus de largeur que de hauteur. Si une page est plus large, elle est considérée comme un paysage `landscape`, et si une page est plus haute, elle est considérée comme un `portrait`.

## A vous de jouer !

1. Reprendre votre code.

2. Rprendre la requête média où vous avez ciblé les écrans ayant une largeur minimale `min-width` de `320px` et une largeur maximale `max-width` de `480px`.

3. Faisons également apparaître le logo et le texte à la verticale si l'écran est en orientation portrait.
    - Ajoutons un autre caractéristique à la règle, en utilisant une virgule (`,`) pour séparer les règles. 
    - Le deuxième élément doit vérifier si l'`orientation` de l'écran est en `portrait.

___
| [Précédent](./14-operateur-and.md)       | [Suivant](./16-point-arrêt.md)       |
