# les requêtes médias ou Media Queries

Le CSS utilise des requêtes média pour adapter le contenu d'un site web à différentes tailles d'écran. Avec les requêtes médias, le CSS peut détecter la taille de l'écran actuel et appliquer différents styles CSS en fonction de la largeur de l'écran.

```css
@media only screen and (max-width: 480px) {
  body {
    font-size: 12px;
  }
}
```

L'exemple ci-dessus montre comment une requête média est appliquée.
La requête média définit une règle pour les écrans de moins de 480 pixels (environ la largeur de nombreux smartphones en orientation paysage).

Cet exemple se décompose en deux éléments:

1. `@media`
    - Ce mot clé lance une règle d'interrogation des médias et indique au compilateur CSS comment analyser le reste de la règle.
 
2. `only screen`
    - Indique les types d'appareils qui doivent utiliser cette règle. Dans les premières tentatives pour cibler différents appareils, le CSS a intégré différents types de médias (écran, impression, ordinateur de poche). Le raisonnement était qu'en connaissant le type de support, les règles CSS appropriées pouvaient être appliquées. Cependant, les appareils "de poche" et "à écran" ont commencé à occuper une gamme beaucoup plus large de tailles et il ne suffisait pas d'avoir une seule règle CSS par appareil.
    - `screen` est le type de support toujours utilisé pour afficher le contenu, quel que soit le type d'appareil. 
    - Le mot-clé `only` est ajouté pour indiquer que cette règle ne s'applique qu'à un seul type de média.
    
3. `and (max-width : 480px)`
    - Cette partie de la règle est appelée *caractéristique média* et demande au compilateur CSS d'appliquer les styles CSS aux appareils d'une largeur de 480 pixels ou moins. Les caractéristiques des médias sont les conditions qui doivent être remplies pour rendre le CSS dans une requête de média.

4. Les règles du CSS sont imbriquées dans les accolades de la requête média. Les règles seront appliquées lorsque la requête média sera satisfaite. Dans l'exemple ci-dessus, le texte dans l'élément body est défini sur une taille de police de `12px` lorsque l'écran de l'utilisateur est inférieur à `480px`.

## A vous de jouer !

1. Reprendre le code [suivant](./versions-exercices/v0-10-11/).

2. Au bas du fichier `style.css`, écrivez une requête média pour une `max-width` de `480px`.
    - Cela nous permettra de réduire la largeur de l'élément `.page-title` sur des écrans plus petits.
  
3. Lorsque la largeur de l'écran est inférieure à `480px`, donnez à la classe `.page-title` une `width` de `270px`.
    - Cela rendra plus clairement sur les petits écrans. Testez votre code en redimensionnant le navigateur.
  
___
| [Précédent](./10-intro-reactivite.md)       | [Suivant](./12-plage.md)        |
