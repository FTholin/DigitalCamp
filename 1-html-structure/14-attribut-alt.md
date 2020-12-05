# L'attribut alt

Pour être un développeur web exceptionnel, il faut notamment rendre votre site accessible aux utilisateurs de tous horizons. Nous devons donc examiner ce qui se passe lorsque des technologies d'assistance telles que les lecteurs d'écran rencontrent des balises d'image.

L'attribut `alt`, qui signifie "texte alternatif", donne un sens aux images de nos sites. L'attribut `alt` peut être ajouté à la balise image tout comme l'attribut `src`. La valeur de `alt` doit être une description de l'image.
```html
<img src="#" alt="Iris bleu" />
```

L'attribut `alt` sert également les objectifs suivants :

- Si une image ne se charge pas sur une page web, un utilisateur peut passer la souris sur la zone initialement prévue pour l'image et lire une brève description de l'image. Ceci est rendu possible par la description que vous fournissez dans l'attribut `alt`.

- Les utilisateurs malvoyants naviguent souvent sur le web à l'aide de logiciels de lecture d'écran. Lorsque vous incluez l'attribut `alt`, le logiciel de lecture d'écran peut lire la description de l'image à haute voix pour l'utilisateur malvoyant.

- L'attribut `alt` joue également un rôle dans l'optimisation des moteurs de recherche (SEO), car les moteurs de recherche ne peuvent pas "voir" les images des sites web lorsqu'ils naviguent sur Internet. Le fait de disposer d'attributs `alt` descriptifs peut améliorer le classement de votre site.

Si l'image sur la page web ne transmet aucune information significative à un utilisateur (malvoyant ou non), l'attribut `alt` doit être laissé vide.

## A vous de jouer !

1. Reprendre votre code duement complété.

2. Ajouter l'attribut `alt` à l'image et inclure une description. Assurez-vous que la description décrit bien l'image.

## Réflexions

1. Quelle devrait être la longueur ou le niveau de détail de notre texte alternatif ?
    - Les attributs `alt` doivent être précis et aussi suffisants que possible. En général, quelques mots seront suffisamment descriptifs, mais parfois une ou deux phrases seront plus appropriées.

___
| [Précédent](./13-image.md)       | [Suivant](./15-video.md)        |
