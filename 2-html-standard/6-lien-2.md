# Lien vers une nouvelle fenêtre

Avez-vous déjà cliqué sur un lien et observé la page web s'ouvrir dans une nouvelle fenêtre de votre navigateur ? Si c'est le cas, vous pouvez remercier l'attribut `target` de la balise `<a>`.

L'attribut `target` précise comment un lien doit s'ouvrir.

Il est possible qu'un ou plusieurs liens de votre page web renvoient à un site web entièrement différent. Dans ce cas, vous pouvez souhaiter que les utilisateurs lisent le site web lié, mais en espérant qu'ils retournent à votre page web. C'est exactement à ce moment-là que l'attribut "target" est utile !

Pour qu'un lien s'ouvre dans une nouvelle fenêtre, l'attribut `target` doit avoir la valeur `_blank`. L'attribut `target` peut être ajouté directement à la balise d'ouverture de l'élément d'ancrage, tout comme l'attribut `href`.
```html
<a href="https://fr.wikipedia.org/wiki/Spiruline_alimentaire" target="_blank">Spiruline</a>
```

Dans l'exemple ci-dessus, le fait de définir l'attribut `target` à "_blank" indique au navigateur d'ouvrir la page Wikipédia concernée dans une nouvelle fenêtre.

Dans cet exercice, nous avons utilisé la terminologie "ouvrir dans une nouvelle fenêtre".

Il est probable que vous utilisiez un navigateur moderne qui ouvre les sites web dans de nouveaux onglets, plutôt que dans de nouvelles fenêtres. Avant l'avènement des navigateurs à onglets, il fallait ouvrir des fenêtres de navigateur supplémentaires pour afficher plus de sites web. L'attribut `target="_blank"`, lorsqu'il est utilisé dans les navigateurs modernes, ouvre de nouveaux sites web dans un nouvel onglet.

## A vous de jouer

1. Reprendre le code de l'exercice et complétez-le.
2. Dans le lien "En savoir plus", ajoutez l'attribut `target` et mettez-le à `_blank`.

## Réflexions

1. Cet exercice utilise la valeur `_blank` pour ouvrir des pages dans de nouveaux onglets. L'attribut `target` a-t-il d'autres valeurs ?
    - Oui, il y a 4 valeurs différentes que l'attribut `target` peut avoir :
        - `_self`
        - `_blank`
        - `_parent`
        - `_top`<br>


Ces valeurs spécifient un contexte de navigation ou l'environnement dans lequel le navigateur affichera un document. Pour en savoir plus sur chacune de ces valeurs, consultez [la documentation de Mozilla](https://developer.mozilla.org/fr/docs/Web/HTML/Element/a) (faites `ctrl+f` et cherchez le mot `target`) !

___

| [Précédent](./5-lien-1.md)       | [Suivant](./7-lien-3.md)        |
