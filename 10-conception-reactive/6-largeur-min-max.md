# Largeur minimum et maximum

Bien que les mesures relatives permettent une mise en page cohérente sur des appareils de tailles d'écran différentes, les éléments d'un site web peuvent perdre leur intégrité lorsqu'ils deviennent trop petits ou trop grands. 
Vous pouvez limiter la largeur d'un élément grâce aux propriétés suivantes :

- `min-width`
  -  garantit une largeur minimale pour un élément.

- `max-width`
  - assure une largeur maximale pour un élément.
 
```css
p {
  min-width: 300px;
  max-width: 600px;
}
```

Dans l'exemple ci-dessus, lorsque le navigateur est redimensionné, la largeur des éléments de paragraphe ne sera pas inférieure à 300 pixels et leur largeur ne dépassera pas 600 pixels.

Lorsqu'une fenêtre de navigateur est réduite ou élargie, le texte peut devenir soit très comprimé, soit très étalé, ce qui le rend difficile à lire. Ces deux propriétés garantissent la lisibilité du contenu en limitant les largeurs minimale et maximale.

Note : L'unité des pixels est utilisée pour garantir des limites strictes sur les dimensions du ou des éléments.

## A vous de jouer !

1. Redimensionnez le navigateur vers la droite. Notez que le texte de la page web peut devenir difficile à lire. Limitons la largeur du texte pour qu'il reste lisible.
    - Dans `style.css`, créez une règle CSS qui fixe la **largeur minimale** de tous les paragraphes à **200 pixels** et exécutez votre code.
    - **Redimensionnez** votre navigateur (rendez-le plus étroit) et remarquez que le texte ne se compresse plus autant qu'avant.
    
   
___
| [Précédent](./5-pourcentage-hauteur-marge.md)       | [Suivant](./7-hauteur-min-max.md)        |
