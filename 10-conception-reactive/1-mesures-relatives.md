# Introduction aux  mesures relatives

La technologie moderne permet aux utilisateurs de naviguer sur internet au moyen de plusieurs appareils, tels que des écrans de bureau, des téléphones portables, des tablettes, etc. Les appareils de tailles d'écran différentes posent toutefois un problème aux développeurs web : comment garantir qu'un site web est lisible et visuellement attrayant sur tous les appareils, quelle que soit la taille de l'écran ?

La conception réactive ou *Responsive Design* fait référence à la capacité d'un site web à redimensionner et à réorganiser son contenu en fonction :

1. La taille des autres contenus du site.
2. La taille de l'écran sur lequel le site web est consulté.

Dans cette leçon, nous allons évaluer la taille du contenu HTML par rapport aux autres contenus d'un site web.

Vous avez sans doute remarqué l'unité de mesure des **pixels**, ou `px`, utilisée dans les sites web.
Les pixels sont utilisés pour dimensionner le contenu aux dimensions exactes.
Par exemple, si vous voulez qu'un `div` soit exactement de 500 pixels de large et de 100 pixels de haut, vous pouvez utiliser l'unité `px`.
Les pixels sont toutefois des valeurs fixes, **codées en dur**.


Lorsqu'une taille d'écran change (comme le passage d'une vue en mode paysage à une vue en mode portrait sur un téléphone), les éléments dimensionnés avec des pixels peuvent apparaître trop petits, déborder de l'écran ou devenir complètement illisibles.
Avec le CSS, vous pouvez éviter les mesures codées en dur et utiliser plutôt des **mesures relatives**.  
Les mesures relatives présentent un avantage par rapport aux mesures codées en dur, car elles permettent de conserver les proportions d'un site web, quelle que soit la taille ou la disposition de l'écran.

___
| [Précédent](../9-affichage-positionnement/pay-n-spray/explications.md)       | [Suivant](./2-em.md)        |
