# Texte stylisé
Vous pouvez également styliser le texte en utilisant des balises HTML. La balise `<em>` met en valeur le texte, tandis que la balise `<strong>` met en valeur le texte important.

Plus tard, lorsque vous commencerez à styliser les sites web, vous déciderez de la manière dont vous voulez que les navigateurs affichent le contenu dans les balises `<em>` et `<strong>`. Toutefois, les navigateurs ont des feuilles de style intégrées qui permettent généralement de donner à ces balises le style suivant:

- La balise `<em>` se traduit généralement par une accentuation en *italique*.

- La balise  `<strong>` aura pour rendu  une accentuation en **gras**.

Jetez un coup d'œil à chaque style en action :

```html
<p><strong>Le Nil</strong> est le <em>plus long</em> fleuve du monde, mesurant plus de 6 850 kilomètres de long (environ 4 260 miles).</p>
```

Dans cet exemple, les balises `<strong>` et `<em>` sont utilisées pour mettre en valeur le texte afin de produire ce qui suit :

> **Le Nil** est le *plus long* fleuve du monde, mesurant plus de 6 850 kilomètres de long (environ 4 260 miles).

Comme on peut le voir, "Le Nil" est en gras et "le plus long" est en italique.

## A vous de jouer !

1. Reprendre votre code précédent duement complété.

2. Dans le premier paragraphe qui commence par "Spirulina Arthrospira Platensis", utilisez la balise `<em>` autour.

3. Dans le même paragraphe, mettez en **gras** les mots "meilleur aliment pour l’humanité au 21ème siècle" en utilisant la balise `<strong>`.

## Réflexions
1. "Les balises fournies par le HTML existent pour organiser et décrire le contenu des pages web". Pourquoi le contenu d'une page web doit-il être décrit à l'aide de balises ?
    - Le navigateur doit savoir quel type de contenu il regarde afin de l'afficher correctement. De plus, d'autres logiciels (lecteurs d'écran, moteurs de recherche, etc.) doivent connaître ces informations afin de pouvoir exécuter correctement des fonctions telles que l'indexation d'une page ou la navigation dans celle-ci.

2. Que signifie : le rendu d'un tag ?
    - Un élément clé d'un navigateur web est son moteur de rendu. Le moteur de rendu prend le code HTML et le rend ou l'interprète en ce que nous voyons visuellement sur la page. Une balise comme `<em>`, associée à la feuille de style par défaut du navigateur, indique au moteur de rendu d'afficher le contenu de cette balise en italique, ce qui met en évidence son contenu.

3. Qu'est-ce qu'une feuille de style ?
    - Dans le contexte du développement web, une feuille de style est un document CSS qui spécifie la présentation du contenu décrit par le HTML associé.  
  En d'autres termes, les feuilles de style donnent du style à nos pages web !

___

| [Précédent](./8-affichage-texte.md)       | [Suivant](./10-saut-ligne.md)        |
