# Flex

La propriété `flex` offre un moyen pratique de spécifier comment les éléments s'étirent et se rétractent, tout en simplifiant le CSS requis. La propriété `flex` vous permet de déclarer `flex-grow`, `flex-shrink` et `flex-basis` sur une seule ligne.

**Remarque** : la propriété `flex` est différente de la valeur `flex` utilisée pour la propriété `display`.

```css
.big {
  flex-grow: 2;
  flex-shrink: 1;
  flex-basis: 150px;
}
 
.small {
  flex-grow: 1;
  flex-shrink: 2;
  flex-basis: 100px;
}
```

Dans l'exemple ci-dessus, tous les éléments ayant la classe `big` augmenteront deux fois plus que les éléments ayant la classe `small`. Gardez à l'esprit que cela ne signifie pas que les grands éléments seront deux fois plus grands que les petits, ils prendront simplement plus de place.

Le CSS ci-dessous déclare ces trois propriétés sur une seule ligne.

```css
.big {
  flex: 2 1 150px;
}
 
.small {
  flex: 1 2 100px;
}
```

Dans l'exemple ci-dessus, nous utilisons la propriété `flex` pour déclarer les valeurs `flex-grow`, `flex-shrink` et `flex-basis` en une ligne.

```css
.big {
 flex: 2 1;
}
```

Dans l'exemple ci-dessus, nous utilisons la propriété `flex` pour déclarer `flex-grow` et `flex-shrink` mais pas `flex-basis`.

```css
.small {
  flex: 1 20px;
}
```

Dans l'exemple ci-dessus, nous utilisons la propriété flex pour déclarer `flex-grow` et `flex-basis`.
Notez qu'il n'est pas possible de définir uniquement `flex-shrink` et `flex-basis` en utilisant 2 valeurs.

Le navigateur à droite comporte deux conteneurs flexibles, chacun avec trois articles flexibles.
Dans `style.css`, examinez les valeurs de chacun de ces éléments. Notez que les valeurs flex-grow et flex-basis sont définies pour les divs bleus.

Étirez la fenêtre du navigateur pour augmenter sa largeur. Observez que lorsque les divs extérieurs supérieurs atteignent 100 pixels de large, ils commencent à croître plus rapidement que le div central supérieur. Remarquez également que lorsque le div inférieur central atteint 100 pixels de large, il commence à croître plus rapidement que les divs extérieurs.

Maintenant, réduisez la fenêtre du navigateur et remarquez que lorsque la fenêtre centrale supérieure atteint 50 pixels de large, elle commence à se rétrécir plus vite que les fenêtres extérieures et lorsque les fenêtres extérieures inférieures atteignent 75 pixels, elles commencent à se rétrécir plus vite que la fenêtre centrale.

## A vous de jouer !

1. Reprendre le code [suivant](./versions-exercices/v0-13-9/):

2. Dans `#top .side`, les trois valeurs `flex-grow`, `flex-shrink` et `flex-basis` sont attribuées individuellement.
   - Les réécrire en une seule ligne.
   
3. Dans `#top .center`, les trois valeurs `flex-grow`, `flex-shrink` et `flex-basis` sont attribuées individuellement.
   - Les réécrire en une seule ligne.
   
4. Dans `#bottom .side`, les trois valeurs `flex-grow`, `flex-shrink` et `flex-basis` sont attribuées individuellement.
   - Les réécrire en une seule ligne.
   
5. Dans `#bottom .center`, les trois valeurs `flex-grow`, `flex-shrink` et `flex-basis` sont attribuées individuellement.
   - Les réécrire en une seule ligne
   
 
___
| [Précédent](./8-flex-basis.md)       | [Suivant](./10-flex-wrap.md)    |
