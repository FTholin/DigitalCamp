# Lien vers une page relative

Jusqu'à présent, vous avez appris à créer des liens vers des pages web externes. De nombreux sites proposent également des liens vers des pages web internes, comme par exemple "Accueil", "À propos" et "Contact".

Avant d'apprendre à établir des liens entre des pages internes, voyons où sont stockés nos fichiers. Lorsqu'ils créent des sites web statiques multipages, les développeurs web stockent souvent les fichiers HTML dans le répertoire racine, ou dans un dossier principal où sont stockés tous les fichiers du projet. Au fur et à mesure que la taille des projets que vous créez augmente, vous pouvez utiliser des dossiers supplémentaires dans le dossier principal du projet pour organiser votre code.

```
dossier-projet/
|—— index.html
|—— info.html
|—— contact.html
```

L'exemple ci-dessus montre trois fichiers différents - `info.html`, `contact.html` et `index.html` - dans un même dossier.

Les fichiers HTML sont souvent stockés dans le même dossier, comme le montre l'exemple ci-dessus. Si le navigateur affiche actuellement `index.html`, il sait également qu'`info.html` et `contact.html` se trouvent dans le même dossier. Comme les fichiers sont stockés dans le même dossier, nous pouvons relier des pages web entre elles en utilisant un chemin d'accès relatif.
```html
<a href="./contact.html">Contact</a>
```

Dans cet exemple, la balise `<a>` est utilisée avec un chemin relatif pour lier le fichier HTML actuel au fichier `contact.html` dans le même dossier. Sur la page web, `Contact` apparaîtra sous la forme d'un lien (comme ceci : [Contact](.)).

Un chemin relatif est un nom de fichier qui indique le chemin vers un fichier local (un fichier sur le même site web, comme `./index.html`) par rapport à un chemin absolu (une URL complète, comme `https://www.exemple.com/learn/learn-html` qui est stockée dans un dossier différent). Le "`./`" dans "`./index.html`" indique au navigateur de rechercher le fichier dans le dossier courrant.



___

| [Précédent](./6-lien-2.md)       | [Suivant](./8-lien-4.md)        |
