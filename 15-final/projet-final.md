# Projet Final

Félicitations, à ce stade de votre parcours de codage, vous pouvez créer des sites web bien conçus et réactifs à partir de zéro.

Vous possédez maintenant les compétences nécessaires pour créer des sites web à partir de zéro ! Il est temps de mettre en pratique tout ce que vous avez appris.

Vous avez la possibilité de réaliser un projet de base en utilisant toutes les compétences que vous avez acquises jusqu'à présent, pour concevoir et créer une page de lancement pour un produit ou un service sortant de votre imagination.

L'objectif de cette activité est de réaliser la même structure architecturale que [maquette.png](./maquette.png) tout en **personnalisant** et **adaptant le contenu** de la page selon vos envies.  

## Critères de rendu

Nous noterons uniquement la forme et **la forme SEULE**. Les contenu des images et du texte est libre (restez décent tout de même).  
Veuillez suivre **à la lettre** les indications sur la maquette. Si et **seulement s'il** n'y a pas d'instruction claire pour une portion de texte, vous pourrez le personnaliser vous-même. Mais l'objectif est de **coller au mieux** à ce qu'il y a sur l'image.  

Description du meilleur scénario : j'ai votre site internet et la maquette côte à côte et je vois la **exactement la même chose sur la forme**. Je regarde un peu votre code. Il est propre. Je met 20/20.

Copier-Coller votre code HTML [ici](https://validator.w3.org/#validate_by_input) afin de vérifier sa validation des standards.

L'organisation du dossier comportant toutes les fichiers pourrait s'organiser comme ci-dessous:

```
├── NOM-PRENOMETUDIANT/        # Dossier à rendre sous format zip
    ├── index.html # fichier contenant le code html
    └── style.css  # fichier contenant le code css
```

Pour les images celles-ci doivent être libres de droit. Voici [le site Pixabay](https://pixabay.com/fr/) très utile  pour récupérer de telles images.

Vous pouvez continuer le travail sur l'éditeur [JsFiddle](https://jsfiddle.net/). Pensez à bien sauvegarder sur votre machine les fichiers si vous ne voulez pas tout perdre !

Aller sur le site [Pixabay](https://pixabay.com/fr/), trouvez des images allant bien avec votre sujet et copier l'adresse de l'image pour la coller dans l'éditeur.  

### Lien vers le dépôt : <a href="https://moodle.ucly.fr/20-21/mod/assign/view.php?id=33814" target="_blank">Cliquez ici</a>

## Barème
| Élément du cours | Critère | Note |
| --------------- | --------------- | --------------- |
| 1-html-structure | Ensemble du contenu HTML demandé | 5 |
| 1-html-structure | Structure composée de plusieurs \<div\> | 1 |
| 1-html-structure | Lien vers d'autres pages web | 1 |
| 1-html-structure | Liens vers la même page | 1 |
| 2-html-standard | HTML standardisé | 0.5 |
| 5-regle-visuelle | Sélecteurs CSS valides | 1 |
| 4-selecteur-css | Enchaînement et spécificité des sélecteurs | 1 |
| 4-selecteur-css | Utilisation cohérente de classes et IDs | 1 |
| 6-couleurs | Utilisation de couleurs Hexa ou RGB | 0.5 |
| 7-typographie | Polices personnalisées liées avec @font-face | 2 |
| 8-modèle-boîte | Bordures et marges de la maquette respectées | 4 |
| 8-modèle-boîte | Gestion des effondrements de marge | 1 |
| 13-flexbox | Aligner efficacement des éléments dans une \<div\> | 1 |

## Structure de la page

La page doit comporter les caractéristiques suivantes:

1. Un header composé de:
  - Un logo ou nom personnalisé 
  - Des liens de navigations pour les différents éléments de la page ([ancrage](https://github.com/FTholin/DigitalCamp/blob/master/2-html-standard/9-lien-5.md))
  - Un bouton pour aller sur Instagram 
  
2. Une section principale :
  - une section inscription pour l'inscription à une newsletter
    - titre h1
    - titre h2
    - paragraphe
    - bouton pour rejoindre
    
3. Une section caractéristique 
  - Caractéristique 1
    - image
    - titre h2
    - titre h3
    
  - Caractéristique 2
    - image
    - titre h2
    - titre h3

4. Une section témoignages
  - titre h2
  - titre h3
  - container d'images
    - image 1
    - image 2
    - image 3
    - image 4
 
5. Une section citation
    - [span](https://developer.mozilla.org/fr/docs/Web/HTML/Element/span) comportant la citation
  
6. Un pied de page
 
    - [span](https://developer.mozilla.org/fr/docs/Web/HTML/Element/span) comportant les droits d'auteurs
    - contenu perso
    
## Pistes d'implémentation
- Les différentes sections seront implémentées avec les `<div>`.
