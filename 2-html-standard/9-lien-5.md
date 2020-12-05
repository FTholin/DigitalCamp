# Lien vers la même page
À ce stade, nous avons tout le contenu que nous voulons sur notre page. Puisque nous avons tant de contenu, tout ne tient pas sur l'écran. Comment pouvons-nous faciliter le passage d'un utilisateur à différentes parties de notre page ?

Lorsque les utilisateurs visitent notre site, nous voulons qu'ils puissent cliquer sur un lien et que la page défile automatiquement vers une section spécifique.

Afin d'établir un lien vers une cible sur la même page, nous devons donner un identifiant à la cible, comme ceci :

```html
<p id="top">Haut de page ! </p>
<div id="bottom">Bas de page ! </div>
```
Dans cet exemple, l'élément `<p>` se voit attribuer un identifiant "top" et l'élément `<div>` un identifiant "bottom". Un identifiant peut être ajouté à la plupart des éléments d'une page web.

Un identifiant doit être bref, afin de faciliter la mémorisation de l'objet d'un lien. Le lien cible est une chaîne de caractères contenant le caractère `#` et l'identifiant de l'élément cible.

```html
<ol>
  <li><a href="#top">Haut</a></li>
  <li><a href="#bottom">Bas</a></li>
</ol>
```
Dans l'exemple ci-dessus, les liens vers `<p id="top">` et `<div id="bottom">` sont intégrés dans une liste ordonnée. Ces liens apparaissent dans le navigateur sous la forme d'une liste numérotée de liens. Un identifiant est particulièrement utile pour organiser le contenu appartenant à une balise `<div>` !  
Exemple de lien : [lien vers le haut](#lien-vers-la-même-page)

## A vous de jouer !

1. Reprendre votre code duement complété.

2. Sous l'élément `<h1>` qui indique `Spiruline`, créez une liste non ordonnée avec les trois éléments de liste suivants :
  - `Introduction`
  - `Habitat`
  - `Médias`

3. Enveloppez le texte de chaque élément de la liste non ordonnée dans un élément d'ancrage. Chaque balise d'ancrage doit comporter un lien vers le `<div>` correspondant de la page (L'élément `<a>` qui contient le texte "Introduction" renvoie à `#introduction`).

___

| [Précédent](./8-lien-4.md)       | [Suivant](./10-bonnes-pratiques.md)        |
