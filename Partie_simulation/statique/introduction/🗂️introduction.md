$$ version 1.0$$
Dans cette  dédiée à l'analyse statique par éléments finis sur SolidWorks 2022. Après avoir conçu, assembler et mettre en plan un système mécanique, il faudra le valider par une analyse par éléments finis pour être sûr que chaque pièce qui le compose résiste bien à l'effort qu'elle subira durant sa durée de vie.

## 1. Méthode des éléments finis

La méthode des éléments finis est technique numérique qui consiste à subdiviser un domaine ( géométrie) en petits éléments, chaque élément est connecté à un autre éléments via des nœuds.
Tout logiciel de simulation par éléments finis comporte trois étapes principales :
- Préprocesseur : Ici il s'agit de définir la géométrie de notre solide avec les outils de conception que nous avions vu dans la première partie de conception, il faudra rajouter des connaissances sur le comportement physique pour bien choisir le modèle mathématique, attribuer les propriétés du matériau, imposer des conditions aux limites, appliquer des forces externes.  
- processeur : Dans cette partie l'utilisateur n'intervient pas beaucoup, il s'agit de résoudre l'équation algébrique du système global.   
- Postprocesseur : Ici on parle de la partie visualisation des résultats des déplacements, de contraintes, de déformations pour vérifier la cohérence des résultats de la simulation.
- 
## 2. Package FE de SolidWorks 

SolidWorks est parmi les logiciel les plus simple à utiliser pour faire non seulement de la conception, assemblage, mais aussi l'analyse par éléments finis. C'est vrai que dans milieu industriel en terme d'analyse il est moins utiliser que d'autres logiciels (Ansys, Comsol, etc), Il faut dire que le package SolidWorks Simulation constitue des fonctionnalités très complètes pour faire n'importe quelle analyse par éléments finis, sa puissance réside entre le passage du modèle CAD dans le cas d'une modification au modèle FEA, SolidWorks détecte et adapte les modifications, de même pour l'organisation de l'analyse dans une arborescence qui facilite la lecture et la modification.

Pour inclure ce package dans SolidWorks il faudrait premièrement avoir une licence parmi lesquelles SW Simulation est inclut.
 
 Tout d'abord cliquez sur le menu "Outil" puis sur "Complément"
 
![[outil_add-In.jpg]]

Vous aurez cette fenêtre, vous cochez les deux cases du package Simulation de SolidWorks.

![[inclure_SW_simulation.jpg]]

Maintenant le package est inclut, pour l'ajouter au ruban des outils, clic droit de la souris sur le ruban, puis "Onglet" puis cochez "Simulation", bien sûr après avoir ouvert un fichier pièce.

![[ruban_simulation.jpg]]


## 3. Premier modèle 

Nous commencerons par une première analyse d'une pièce très connue par les menuisiers, sculpteurs de bois, il s'agit d'un burin pour bois. Le modèle CAO "burin.sldprt" est prêt vous pouvez directement l'ouvrir sur SolidWorks.

![[burin.jpg]]

Pour démarrer une nouvelle étude statique cliquez sur la flèche du bouton "Nouvelle étude" puis sur "Nouvelle étude" comme la figure suivante.

![[outil_nouvelle_etude.png]]

Choisissez "statique", vous pouvez insérer un nom pour cette nouvelle étude, dans mon cas je l'ai laissé par défaut, puis validez.

![[etude_statique.jpg]]

Vous constatez que tous les boutons du ruban sont désormais actifs.

Pour faire une analyse statique en élément fini il nous : 
1- Définir des conditions aux limites : dont les charges et les déplacements imposés; 
2- Définir un maillage: qui dépendra de la complexité de géométrie de notre pièce;
3- 
