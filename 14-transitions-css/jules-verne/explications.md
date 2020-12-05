# Projet Vingt mille lieux sous les mers

Dans ce projet, vous suivrez des instructions étape par étape pour ajouter des animations à une page web statique existante. La page web est un lecteur en ligne ; elle présente le texte intégral du livre "20 000 lieues sous les mers" de Jules Verne.


La page du premier chapitre est pratiquement complète. Il y a quelques éléments de fantaisie :

- Lorsque vous survolez la barre latérale à gauche, un menu s'ouvre et contient la table des matières.
- Lorsque vous survolez un mot en surbrillance dans le texte, une définition apparaît. Voir les mots "phosphorescent" et "locomotion".
- Lorsque vous survolez les boutons semi-transparents en bas de page, ils deviennent opaques.
- Lorsque vous survolez un lien, il change de couleur.

Ces interactions ajoutent un niveau de raffinement à une page par ailleurs statique. 
Votre travail consistera à les affiner encore plus. 
Actuellement, tous ces changements se font en un instant.
Ajoutez des transitions pour que les changements se fassent en douceur.

1. Reprendre le code [suivant](/exercices-versions/v0-14-1).

2. Dans `style.css`, trouvez le sélecteur de liens à l'intérieur de la barre latérale (`nav a`). Ajoutez une déclaration CSS pour la transition de la couleur du texte. Expérimentez avec différentes valeurs pour la durée, la fonction de temporisation et le délai jusqu'à ce que vous soyez satisfait.

3. Ensuite, vous animerez la transparence des boutons "Suivant" et "Précédent".
   Trouvez le sélecteur de la classe "bouton" (`.button`). Ajoutez une déclaration de transition de l'opacité de la propriété. Là encore, le choix pour les autres valeurs est à vous. Choisissez des valeurs de durée, de fonction de temporisation et de délai qui vous conviennent.

4. Maintenant, faites glisser la barre latérale au lieu de la faire apparaître instantanément. Ajoutez une déclaration au sélecteur de navigation pour faire la transition avec la propriété de gauche. Expérimentez avec les autres propriétés de transition.

5. Trouvez le sélecteur `.definable .word` qui sélectionne les mots qui ont des définitions. Ajouter une transition pour la couleur du texte.

6. Enfin, nous allons faire tomber le bloc de définition du haut de la page et le faire apparaître en fondu enchaîné. Le sélecteur pour cette section est `.definable .definition-container`. Ajoutez une déclaration pour faire la transition avec la propriété supérieure. Utilisez une virgule (`,`) pour faire la transition avec une deuxième propriété, l'opacité.

___

| [Précédent](./5-combinaisons.md)       | [Quiz](https://moodle.ucly.fr/20-21/mod/quiz/view.php?id=32993)      |     [Suivant : 15-final](../../15-final/1-mise-en-place-git.md)     |
