# Headings ou Titres

Les titres en HTML sont similaires aux titres des autres types de médias. Par exemple, dans les journaux, de grandes rubriques sont généralement utilisées pour attirer l'attention du lecteur. D'autres fois, les titres sont utilisés pour décrire un contenu, comme le titre d'un film ou d'un article éducatif.

Le HTML suit un schéma similaire. En HTML, il existe six titres différents, ou éléments de titre. Les titres peuvent être utilisés à des fins diverses, comme le titrage de sections, d'articles ou d'autres formes de contenu.

Voici la liste des éléments de titre disponibles en HTML. Ils sont classés par ordre de taille, du plus grand au plus petit.

1. `<h1>` : utilisé pour les rubriques principales. Toutes les autres petites rubriques sont utilisées pour les sous-rubriques.
2. `<h2>`
3. `<h3>`
4. `<h4>`
5. `<h5>`
6. `<h6>`

L'exemple de code suivant utilise un titre destiné à attirer l'attention du lecteur. Il utilise le plus grand titre disponible, l'élément principal du titre :

```html
<h1>J'accuse !</h1>
```

## A vous de jouer !

1. Copier et coller le code [suivant](./projet-spiruline/v0-1-5.html)

>Maintenant que vous savez comment structurer les éléments HTML, nous allons passer le reste de la leçon à construire un site web d'information en utilisant certains des éléments HTML les plus courants. Nous avons ajouté quelques éléments pour vous aider à démarrer, mais vous écrirez le reste de la page vous-même.

2. Sous le titre `<h3>` qui indique `Bienfaits`, ajoutez un titre `<h2>` qui indique `Habitat naturel`.

3. Sous le titre `Habitat naturel`, ajoutez un titre `<h3>` qui indique `Amérique`.

4. Sur la ligne suivante, ajoutez un autre titre `<h3>` qui indique `Afrique`.

5. Enfin sur la ligne suivante, ajoutez un titre `<h2>` qui dit `Image`.


## Réflexions

1. Comment savoir quel élément de la rubrique choisir ? Par exemple, pourquoi avons-nous utilisé les balises `<h1>` pour le titre `Spiruline` mais les balises `<h3>` pour `Bienfaits`
   - Les éléments de titre doivent être choisis de manière à refléter la manière dont le contenu de notre page doit être organisé. Plus tard dans cette leçon, vous utiliserez l'élément `<div>` pour diviser cette page en plusieurs sections. Chacune de ces sections aura un titre contenu dans les balises `<h2>` et divers sous-titres qui sont contenus dans les balises `<h3>`.  

Exemple :  
Comme le titre `Spiruline` est le titre principal de ce document, nous utilisons ici les balises `<h1>`.  
Comme `Bienfaits` est un sous-titre de la section `Description` de la page (qui sera éventuellement plus clairement délimitée avec des éléments `<div>`), nous utilisons les balises `<h3>` pour contenir ce titre.


___
| [Précédent](./4-structure.md)       | [Suivant](./6-div.md)        |
