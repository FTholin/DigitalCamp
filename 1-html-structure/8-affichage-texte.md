# Afficher du texte
Si vous souhaitez afficher du texte en HTML, vous pouvez utiliser un paragraphe ou une plage :

- Les paragraphes `<p>` contiennent un bloc de texte en clair.

- `<span>` contient de courts morceaux de texte ou d'autres HTML. Ils sont utilisés pour séparer les petits morceaux de contenu qui se trouvent sur la même ligne que d'autres contenus.

Jetez un coup d'œil à chacun de ces éléments en action ci-dessous :

```html
<div>
  <h1>Technologie</h1>
</div>
<div>
  <p><span>Le cerf volant éolienne</span> est la technologie clé pour la production d'énergie éolienne par des vents de haute altitude.</p>
</div>
```

Dans l'exemple ci-dessus, il y a deux `<div>` différents. Le second `<div>` contient un `<p>` avec `<span>Le cerf volant éolienne</span>`. Cet élément `<span>` sépare "Le cerf volant éolienne" du reste du texte du paragraphe.

Il est préférable d'utiliser un élément `<span>` lorsque vous souhaitez cibler un contenu spécifique qui est en ligne, ou sur la même ligne que d'autres textes. Si vous souhaitez diviser votre contenu en blocs, il est préférable d'utiliser un élément `<div>`.

## A vous de jouer !

1. Reprendre votre code précédent dument complété.

2. Sous l'élément `<h2>` qui dit `Description`, ajoutez les balises `<p>` d'ouverture et de fermeture, et à l'intérieur de ces balises, mettez le texte suivant :
  > Spirulina Arthrospira Platensis, est une cyanobactérie filamenteuse de couleur bleue verte en forme de spirale, elle dispose de nombreux bienfaits sur la santé à l’origine de sa popularité. Il est possible de la retrouver sous la forme de poudre, de paillettes, en comprimés ou bien encore en gélules.
  Classée dans la famille des “super aliments”, la spiruline est en aussi considérée par l’Organisation Mondiale de la Santé (OMS) comme comme le meilleur aliment pour l’humanité au 21ème siècle et le plus complet du fait de sa composition et de sa richesse nutritionnelle exceptionnelle.

N'oubliez pas de toujours ajouter deux espaces d'indentation lorsque vous emboîtez des éléments à l'intérieur de `<div>` pour une meilleure lisibilité.

3. Sous l'élément `<h3>` qui dit `Bienfaits`, ajoutez un paragraphe avec le texte suivant :
  > Antioxydant, anti-âge, stimulant du système immunitaire, détoxifiant, lutte contre l'anémie et les carences, diminution du taux de cholestérol, stimulant et tonifiant de l'organisme, antiradiations, régulateur de glycémie.

___

| [Précédent](./7-attributs.md)       | [Suivant](./9-texte-stylisé.md)        |
