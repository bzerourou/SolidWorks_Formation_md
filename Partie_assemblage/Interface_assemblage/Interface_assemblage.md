$$version 1.0$$

Cette première section est une brève introduction au projet d'assemblage sur SolidWorks, elle contient un premier contact avec l'interface déjà connue, mais un plus spécifique. 

# Sommaire :

## I. Création et importation

#### a. Création

Pour créer un nouvel assemblage sur SolidWorks rien de plus simple, sur la page de démarrage, on clique sur le menu Fichier, puis sur le bouton nouveau.

![image1](..\Attachements)

ça va nous faire sortir la première boite de dialogue que nous avions déjà comment l'utilisé, cette fois-ci on clique sur le bouton assembalge.

![](..\Attachements\nouveau_assemblage.jpg)

et Vous aurez cette nouvelle interface dédiée à l'assemblage, elle est la même que celle de la partie conception, mais elle importe cette fois-ci les outils nécessaires pour les assemblages que nous réaliserons plus tard.

![](..\Attachements\assemblage_interface.jpg)

1. Le bandeau des outils principaux; 
2. L'arbre des pièces qui seront importées, ainsi que les contraintes d'assemblages;
3. Menu des options, boite d'importation.

#### b. Importation

Pour importer des pièces il vous suffit de cliquer sur le bouton de la fonction "Insérer des composants".

![](..\Attachements\outil_importation.jpg)

une boite de dialogue s'ouvre et vous pouvez sélectionner pièce par pièce ou directement toutes pièces que vous voulez d'un seul coup, même si je ne recommande pas cette dernière.
Commençons par importer la première pièce qui est la vis. 

![](..\Attachements\selection_vis.jpg)

Une fois l'opération d'importation validée, SolidWorks vous donnera la possibilité de faire translater la pièce dans n'importe quelle position sur la fenêtre de travail, vous choisissez cette position et elle sera ensuite fixée et vous ne pourriez plus la déplacée. 

POur être plus précis de la façon dont on oriente la pièce on va se servir des cretaines fonctionnalité, comme la figure suivante.

![](..\Attachements\assemblage_vis_import.jpg)Maintenant on va se servir des trois fonctionnalités d'orientations sur notre pièces, si avec la souris vous faites pivoter la pièce vers le **bouton x**, et vous cliquez sur lui, la pièce va pivoter normal à votre écran.

![](..\Attachements\assemblage_vis_import_x.jpg)

Dans le cas où  vous cliquez sur le **bouton z**, la pièce va so'rienter horizontalement à votre écran.

![](..\Attachements\assemblage_vis_import_z.jpg)

Il y a aussi une possibilité de changer l'orientation du plan de l'espace de travail en cliquant sur l'une des flèches su système de coordonnées principales de SolidWorks, comme la figure suivante, dans mon cas j'ai cliqué sur la **flèche x**.

![](..\Attachements\assemblage_vis_import_z_fx.jpg)

Pour savoir si votre pièce est fixée un signe (f) va précéder le nom de la pièce comme dans la figure suivante.

![](..\Attachements\piece_fixee.jpg)

Vous pouvez répéter l'opération pour importer l'écrou, cette fois-ci la pièce est libre car son nom est précédé par (-).

![](..\Attachements\assemblage_ecrou.jpg)

#### c. Enregister l'assemblge

Il faudra penser à enregistrer nos assemblages en fur et à mesure qu'on avancera dans nos projet, pour cela il faut tout cliquer sur le bouton "enregistrer " su menu Fichier. puis donner un nom à notre fichier d'assemblage.

![](..\Attachements\enregister_assemblage.jpg)

Les fichiers d'assemblage sous SolidWorks ont l'extension **".sldasm"**.

#### d. Fonctions de bases sur les assemblages

###### 1- Origine pièce/environnement

L'une des notion les plus importante dans l'importation des pièces pour les assemblages et l'origine de la pièce et l'orgine de l'envoronement SolidWorks, il faut toujours les faire coincider.

Nous avions appris à importer les pièces, mais au moment de l'import il faut s'assurer de la coincidence des origines pièce/environnement, car ça va nous faciliter la tâche dans le future.

Si je reviens à mon exemple, de vis-écrou, on avait pas fait attention à faire correspondre l'origine de la pièce avec celle de SolidWorks, pour faire ça, il vous suffit seulement où moment de l'importation de cliquer sur le bouton de visibilité qui a une icone d'oeuil, et de choisir 

![](..\Attachements\assemblage_origine_visib.jpg)

Le résultat sera que les deux origines vont apparaitre dans votre projet d'assemblage.

![](..\Attachements\assemblage_origine_active.JPG)

Il ne vou reste que de faire pivoter votre pièce vers l'origine SolidWorks et de valider en liquant sur le bouton droit de la souris pour créer certe première contrainte.

![](..\Attachements\assemblage_contrainte_origines.jpg) 

###### 2- Menu contextuel

Quand on clique sur le bouton droit de la souris, on aura un menu avec lequel il nous y est possible de faire beaucoup de choses : 

- Fixer / bouger ou libérer une pièce : avec cette fonctionnalité vous serez capable de fixer ou de faire translater vos pièces ;

- ###### 3- Assemblage sur place

Il existe un moyen de faire un assemblage sur place, cela veut dire qu'on peut se servir des fonctionnalités de conception dans un projet d'assemblage dans SolidWorks pour créer une pièce qui ne sera pas référencer de l'extérieur de projet comme on vient de le faire en haut.

Ces pièces ne seront visible que dans le projet d'assemblage.

###### 4- Créer un sous-assemblage

Il est possible de créer autant de sous-assemblages qu'on veut sur SolidWorks, 

###### 5- Enregistrer les composants dans des fichiers externes

Il existe un moyen qui nous permettra comme même de sauver les composants qu'on peut créer dans un projet d'assemblage dans des fichiers externes.
