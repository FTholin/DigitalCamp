# Rem

La deuxième unité de mesure relative dans le CSS est le `rem`, codé comme `rem`.

Rem signifie **Racine** `em`. Il agit de manière similaire à em, mais au lieu de vérifier les éléments parents pour la taille de la police, il vérifie l'élément racine.
L'élément racine est la balise `<html>`.

La plupart des navigateurs fixent la taille de la police de `<html>` à *16 pixels*, donc par défaut les mesures de rem seront comparées à cette valeur.
Pour définir une taille de police différente pour l'élément racine, vous pouvez ajouter une règle CSS.

```css
html {
  font-size: 20px;
}

h1 {
  font-size: 2rem;
}
```

Dans l'exemple ci-dessus, la taille de police de l'élément racine, `<html>`, est fixée à *20 pixels*.  
Toutes les mesures `rem` ultérieures seront maintenant comparées à cette valeur et la taille des éléments `h1` dans l'exemple sera de *40 pixels*.

L'un des avantages de l'utilisation de `rems` est que tous les éléments sont comparés à la même valeur de taille de police, ce qui permet de prévoir facilement la taille de police.  
Si vous souhaitez dimensionner les éléments de manière cohérente sur l'ensemble d'un site web, la mesure `rem` est la meilleure unité pour ce travail.

Si vous souhaitez dimensionner des éléments par rapport à d'autres éléments voisins, l'unité `em` est plus adaptée au travail.

## A vous de jouer !

1. Reprendre votre code.

2. Dans `style.css`, ajoutez une nouvelle règle sur la ligne 3 qui fixe la taille de police de l'élément racine à **16 pixels**.

```css
  html {
    font-size: 16px;
  }
  ```
  
3. Mettons à jour les tailles de police que vous avez définies dans précédemment pour utiliser `rem` au lieu de `em`.
    - Tout d'abord, modifiez la taille de police dans `#banner h1` à `3.75rem`.
    
4. Définissez la taille de police de `.post h2` à `1.875rem`.

5. Définissez la taille de police dans `.post h3` à `1.125rem`.

6. Définissez la taille de police de `footer` à `1.125rem`.



___
| [Précédent](./2-em.md)       | [Suivant](./4-pourcentage-hauteur-largeur.md)        |
