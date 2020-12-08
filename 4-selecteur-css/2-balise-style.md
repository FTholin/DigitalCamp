# Balise `<style>` dans `<html>`

Les styles en ligne sont un moyen rapide de styliser le HTML, mais ils ont aussi leurs limites. Si vous vouliez styliser, par exemple, plusieurs éléments `<h1>`, vous devriez ajouter manuellement un style en ligne à chaque élément. En outre, vous devez également maintenir le code HTML lorsque des éléments `<h1>` supplémentaires sont ajoutés.

Heureusement, le HTML vous permet d'écrire du code CSS dans sa propre section dédiée avec l'élément `<style>`. Le code CSS peut être écrit entre les balises `<style>` d'ouverture et de fermeture. Pour utiliser l'élément `<style>`, il doit être placé à l'intérieur de l'élément `<head>`.

```html
<head>
  <style>


  </style>
</head>
```

Après avoir ajouté une balise `<style>` dans la section head, vous pouvez commencer à écrire du code CSS.

```html
<head>
  <style>
    p {
      color: red;
      font-size: 20px;
    }
  </style>
</head>
```

Le code CSS dans l'exemple ci-dessus change la couleur de tout le texte des paragraphes en rouge et change également la taille du texte à 20 pixels. Notez comment la syntaxe du code CSS correspond (pour l'essentiel) à celle que vous avez utilisée pour le style en ligne. La principale différence est que vous pouvez spécifier les éléments auxquels appliquer le style. Le caratère `p`, ici, veux dire "sélectionne et modifie TOUS les `<p>`.

Là encore, les détails de la syntaxe CSS dans l'exemple ci-dessus ne sont pas importants pour le moment. Vous en apprendrez davantage sur les détails de la syntaxe CSS dans les prochaines leçons.

## A vous de jouer !

1. Reprendre votre code duement complété.
2. Tout d'abord, ajoutez un élément `<style>` dans la balise `<head>`, l'entête du HTML. Ensuite, veillez à supprimer les styles en ligne que vous avez ajoutés au paragraphe.

3. Ajoutez le style en ligne que vous avez supprimé de l'élément `<p>` à l'élément `<style>` dans l'entête `<head>`.

## Réflexions
1. Il semble étrange de réunir deux langues dans un seul document. Est-ce une pratique courante ?
    - Sur le web, il n'est pas rare de voir deux langues s'entremêler de cette manière, surtout si l'on regarde des sites plus anciens. Par exemple, certains sites associent de manière similaire les langages JavaScript et HTML.
    - Si ce type de couplage étroit n'est pas si rare, ce n'est pas une grande habitude à prendre. En tant que développeurs, nous devons nous efforcer de "séparer nos préoccupations". Dans le cas du CSS, cela signifie que nous voudrons généralement garder notre CSS en dehors de notre document HTML. En d'autres termes, il est préférable d'utiliser des fichiers `.css` plutôt que de définir nos styles en ligne ou dans la balise `<style>`. 

___

| [Précédent](./1-style-en-ligne.md)       | [Suivant](./3-fichier-css.md)        |
