# Structure HTML

Le HTML est organisé comme une collection de relations d'arbres généalogiques. Comme vous l'avez vu dans le dernier exercice, nous avons placé des balises `<p>` dans des balises `<body>`. Lorsqu'un élément est contenu à l'intérieur d'un autre élément, il est considéré comme l'enfant de cet élément. L'élément enfant est dit être emboîté à l'intérieur de l'élément parent.

```html
<body>
  <p> Ce paragraphe est un 'enfant' de body </p>
</body>
```

Dans l'exemple ci-dessus, l'élément `<p>` est imbriqué dans l'élément `<body>`. L'élément `<p>` est considéré comme un enfant de l'élément `<body>`, et l'élément `<body>` est considéré comme le parent. Vous pouvez également voir que nous avons ajouté deux espaces d'indentation (en utilisant la barre d'espacement) pour une meilleure lisibilité.

Comme il peut y avoir plusieurs niveaux d'imbrication, cette analogie peut être étendue aux petits-enfants, aux arrière-petits-enfants, et au-delà. La relation entre les éléments et leurs éléments ancêtres et descendants est connue sous le nom de hiérarchie.

Considérons un exemple plus compliqué qui utilise de nouvelles balises :

```html
<body>
  <div>
    <h1>élément frère de 'p', mais aussi petit-fils de 'body'</h1>
    <p>élément frère de 'h1', mais aussi petit-fils de 'body'</p>
  </div>
</body>
```

Dans cet exemple, l'élément `<body>` est le parent de l'élément `<div>`. Les éléments `<h1>` et `<p>` sont tous deux des enfants de l'élément `<div>`. Comme les éléments `<h1>` et `<p>` sont au même niveau, ils sont considérés comme des frères et sœurs et sont tous deux petits-enfants de l'élément `<body>`.

Il est important de comprendre la hiérarchie HTML car les éléments enfants peuvent hériter du comportement et du style de leur élément parent. Vous en apprendrez plus sur la hiérarchie des pages web lorsque vous commencerez à creuser dans le CSS.


## A vous de jouer !
1. Copier et coller le code suivant:
  ```html
  <body>
    <h1>Hello World</h1>

    <div>
      <h1>élément frère de 'p', mais aussi petit-fils de 'body'</h1>
      <p>élément frère de 'h1', mais aussi petit-fils de 'body'</p>

      <section>
        <p>Fils de 'section' et arrière petit-fils de 'body'</p>
      </section>
    </div>
  
</body>
```
1. Ajouter le code ci-dessous en tant que petit-fils de l'élément div.
```html
<p>Ce paragraphe est petit-fils de l'élément 'div'</p>
```


## Réflexions

1. Est-il correct de dire que l'élément `<body>` est **imbriqué** dans l'élément `<html>` ?
    - C'est exact ! La balise `<html>` est l'élément racine de chaque page et elle devrait toujours avoir des éléments enfants `<head>` et `<body>`. Les éléments `<head>` et `<body>` sont des frères et soeurs entre eux et des enfants pour le parent `<html>`.

2. Dans les étapes 1 et 2 de cet exercice, les deux éléments `<p>` s'affichent exactement de la même manière. Comme il ne semble pas que quelque chose de spécial se soit produit ici, quel est l'intérêt d'emboîter l'élément `<p>` dans un élément `<div>` ?
    - Dans ce cas, cela est fait à des fins purement démonstratives. À l'avenir, vous constaterez que les éléments `<div>` sont souvent utilisés pour regrouper des contenus connexes. Cela peut servir à donner à une page une structure supplémentaire et à permettre un style plus modulaire.

3. Cet exercice indique que les éléments de l'enfant peuvent hériter de leurs parents. Quelles sortes de choses les enfants peuvent-ils hériter de leurs parents ?
    - En vous plongeant dans notre cours CSS, vous apprendrez que les éléments enfants héritent de la plupart de leur style des éléments parents. En d'autres termes, la plupart des styles descendent en cascade des parents vers les enfants.

___
| [Précédent](./3-body.md)       | [Suivant](./5-headings.md)        |
