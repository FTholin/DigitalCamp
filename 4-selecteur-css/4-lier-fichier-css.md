# Lier le fichier CSS

Parfait ! Nous avons réussi à séparer la structure (HTML) du style (CSS).

Lorsque le code HTML et le code CSS sont dans des fichiers séparés, les fichiers doivent être liés. Sinon, le fichier HTML ne pourra pas localiser le code CSS, et le style ne sera pas appliqué.

Vous pouvez utiliser l'élément `<link>` pour lier les fichiers HTML et CSS ensemble. L'élément `<link>` doit être placé dans l'en-tête du fichier HTML. Il s'agit d'une balise à fermeture automatique qui requiert les trois attributs suivants :

1. `href` : comme l'élément ancre `<a>`, la valeur de cet attribut doit être l'adresse, ou le chemin, du fichier CSS.
2. `type` : cet attribut décrit le type de document auquel vous vous connectez (dans ce cas, un fichier CSS). La valeur de cet attribut doit être fixée à `text/css`.
3. `rel` : cet attribut décrit la relation entre le fichier HTML et le fichier CSS. Étant donné que vous établissez un lien avec une feuille de style, la valeur doit être `stylesheet`.

Lorsque vous liez un fichier HTML et un fichier CSS ensemble, l'élément `<link>` ressemblera à ce qui suit :


```html
<link href="http://monUrl.fr/mon-site/css/style.css" type="text/css" rel="stylesheet">
```

Notez que dans l'exemple ci-dessus, le chemin d'accès à la feuille de style est une URL :

La spécification du chemin d'accès à la feuille de style à l'aide d'une URL est une façon de lier une feuille de style.

Si le fichier CSS est stocké dans le même répertoire que votre fichier HTML, vous pouvez alors spécifier un chemin relatif au lieu d'une URL, comme cela :

```html
<link href="./style.css" type="text/css" rel="stylesheet">
```

L'utilisation d'un chemin relatif est une façon très courante de relier une feuille de style.

## A vous de jouer !

1. Relions la feuille de style CSS au fichier HTML.

    Tout d'abord, ajoutez un élément `<link>` dans la section `<head>`.

2. Ensuite, ajoutez l'attribut `href` à l'élément `<link>` et mettez-le égal à `style.css`.

3. Ensuite, ajoutez l'attribut type et fixez-le à la valeur correcte.

4. Enfin, ajoutez l'attribut `rel` et fixez-le à la valeur correcte. Gardez un œil sur la police du premier paragraphe - elle devrait apparaître différente des descriptions des destinations lorsque votre feuille de style est correctement liée.


## Réfléxions

Comment puis-je lier ma feuille de style CSS à un fichier HTML ?
- Vous pouvez insérer cette balise dans la section `<head>` de votre fichier HTML :  
   `<link rel="stylesheet" type="text/css" href="mon_fichier_css.css" />`  

  Afin de déterminer le chemin d'accès à votre fichier css, vous devez déterminer où se trouve votre fichier html par rapport à votre fichier css. Considérez les quatre scénarios (NOTE : nom de dossier et nom de fichier css sont les noms de vos dossiers et de votre fichier css) :
  1. Votre fichier css se trouve dans le même dossier que votre fichier html. Le chemin d'accès à votre fichier sera alors le suivant : `./mon_fichier_css.css`

  2. Votre fichier css se trouve dans un autre dossier qui se trouve dans le même dossier que votre fichier html.
Le chemin d'accès à votre fichier sera alors `./nomdudossier/mon_fichier_css.css`
Si votre fichier css est imbriqué dans plus d'un dossier, ajoutez un autre /folderName jusqu'à ce que vous arriviez à votre fichier.
  `<link rel="stylesheet" type="text/css" href="mon_fichier_css" />`
  
  3. Votre fichier css se trouve dans un autre dossier en dehors de votre fichier html. Votre chemin d'accès est alors : `../mon_fichier_css.css`  
  
      Si votre fichier css se trouve dans plusieurs dossiers en dehors de votre fichier html, alors vous ajouterez un `../` pour chaque dossier qui se trouve en dehors.

___
| [Précédent](./3-fichier-css.md)       |[Suivant](./5-balise-name.md)        |
