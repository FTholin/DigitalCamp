# Propriétés ARIA

Les propriétés ARIA sont des attributs que vous pouvez ajouter aux éléments HTML. Ces attributs fournissent des informations supplémentaires sur des éléments qui peuvent ne pas être évidents pour les utilisateurs de lecteurs d'écran.
Examinons une propriété appelée `aria-label`.

```html
<img src="#" alt="A painting of the Shenandoah Valley"/>
<p>Armand Cabrera, 2010</p>
```

Dans l'exemple ci-dessus, une personne regardant la page web verrait probablement "Armand Cabrera" sous l'image et utiliserait des indices visuels pour en déduire qu'il est l'artiste. Cependant, pour une personne utilisant un lecteur d'écran, il se peut que la signification du paragraphe situé sous l'image ne soit pas claire.
La propriété `aria-label` donne au lecteur d'écran des informations supplémentaires à lire à haute voix à l'utilisateur.

```html
<img src="#" alt="A painting of the Shenandoah Valley"/>
<p aria-label="Artist">Armand Cabrera, 2010</p>
```

Dans le HTML amélioré ci-dessus, l'utilisateur d'un lecteur d'écran saura comment ce paragraphe se rapporte à l'image qui se trouve au-dessus de lui.

D'autres propriétés d'ARIA sont utiles pour les sites web plus complexes utilisant des formulaires HTML, JavaScript et d'autres outils avancés.

Pour une liste complète des propriétés ARIA [cliquez ici](https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA/ARIA_Techniques).

## A vous de jouer !

1. Reprendre votre code.

2. Dans la balise `<p>` contenant `1840`, ajoutez un attribut `aria-label` qui dit "date de la photo de Ada".

3. Dans la balise `<p>` contenant `1850`, ajoutez un attribut `aria-label` qui dit "date de la photo de Babbage".
    - Nous ajouterons la propriété `aria-label` appropriée aux autres cases contenant les dates des images pour vous.
    
___
| [Précédent](./3-aria.md)       | [Suivant](./5-attribut-alt.md)    |
