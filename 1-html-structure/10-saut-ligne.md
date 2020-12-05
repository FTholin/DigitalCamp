# Saut à la ligne
L'espacement entre les balises dans un fichier HTML n'affecte pas le positionnement des éléments dans le navigateur. Si vous souhaitez modifier l'espacement dans le navigateur, vous pouvez utiliser l'élément de saut de ligne de HTML : `<br>`.

L'élément de saut de ligne est unique car il est composé uniquement d'une balise de départ. Vous pouvez l'utiliser n'importe où dans votre code HTML et un saut de ligne sera affiché dans le navigateur.

```html
<p>Le Nil est le plus long des fleuves <br> dans le monde, soit plus de 6 850 <br> kilomètres de long (environ 4 260 miles).</p>
```

Le code dans l'exemple ci-dessus donnera un résultat qui ressemblera à ce qui suit :
```html
Le Nil est le plus long des fleuves
dans le monde, soit plus de 6 850
kilomètres de long (environ 4 260
miles).
```

## A vous de jouer !

1. Reprendre le code de l'exercice précédent complété.

2. Ajoutez un sauts de ligne (`<br>`) après la phrase "...santé à l’origine de sa popularité".


## Réflexions

1. Si l'espacement dans nos documents HTML n'affecte pas le positionnement du contenu sur la page, pourquoi devons-nous utiliser des indentations à deux espaces ?
    - Les développeurs expérimentés utilisent l'indentation et l'espacement vertical pour garder leur code propre et lisible. Un code très lisible améliore la maintenabilité, facilite les efforts de collaboration et améliore l'expérience du développeur en général. Dans notre HTML, une indentation cohérente doit être utilisée pour illustrer l'imbrication.

2. Si les deux `<br>` et `<br />` sont des syntaxes valables, laquelle dois-je utiliser ?
    - Il n'y a pas de consensus à ce sujet et l'une ou l'autre des syntaxes est acceptable. Quelle que soit la syntaxe que vous choisissez, veillez à ce qu'elle soit cohérente.

3. Les sauts de ligne sont-ils la façon habituelle de manipuler la position des éléments HTML ?
    - Pour l'instant, comprenez simplement que dans le développement web, il existe un principe de conception appelé séparation des préoccupations. Ce principe nous guide pour garder notre structure HTML distincte de sa présentation. Comme la mise en page est une présentation, nous voudrons généralement utiliser le CSS pour positionner nos éléments.

___

| [Précédent](./9-texte-stylisé.md)       | [Suivant](./11-liste-non-ordonnée.md)        |
