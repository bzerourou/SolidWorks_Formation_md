$$version 1.0$$

Cette première section est une brève introduction au projet d'assemblage sur SolidWorks, elle contient un premier contact avec l'interface déjà connue, mais un plus spécifique. 

# Sommaire :

## I. Création et importation

#### a. Création

Pour créer un nouvel assemblage sur SolidWorks rien de plus simple, sur la page de démarrage, on clique sur le menu Fichier, puis sur le bouton nouveau.

![image1](../Attachements/outil_nouveau.jpg)

ça va nous faire sortir la première boite de dialogue que nous avions déjà comment l'utilisé, cette fois-ci on clique sur le bouton assembalge.

![](../Attachements/nouveau_assemblage.jpg)

et Vous aurez cette nouvelle interface dédiée à l'assemblage, elle est la même que celle de la partie conception, mais elle importe cette fois-ci les outils nécessaires pour les assemblages que nous réaliserons plus tard.

![](../Attachements/assemblage_interface.jpg)

1. Le bandeau des outils principaux; 
2. L'arbre des pièces qui seront importées, ainsi que les contraintes d'assemblages;
3. Menu des options, boite d'importation.

#### b. Importation

Pour importer des pièces il vous suffit de cliquer sur le bouton de la fonction "Insérer des composants".

![](../Attachements/outil_importation.jpg)

une boite de dialogue s'ouvre et vous pouvez sélectionner pièce par pièce ou directement toutes pièces que vous voulez d'un seul coup, même si je ne recommande pas cette dernière.
Commençons par importer la première pièce qui est la vis. 

![](../Attachements/selection_vis.jpg)

Une fois l'opération d'importation validée, SolidWorks vous donnera la possibilité de faire translater la pièce dans n'importe quelle position sur la fenêtre de travail, vous choisissez cette position et elle sera ensuite fixée et vous ne pourriez plus la déplacée. 

POur être plus précis de la façon dont on oriente la pièce on va se servir des cretaines fonctionnalité, comme la figure suivante.

![](../Attachements/assemblage_vis_import.jpg)Maintenant on va se servir des trois fonctionnalités d'orientations sur notre pièces, si avec la souris vous faites pivoter la pièce vers le **bouton x**, et vous cliquez sur lui, la pièce va pivoter normal à votre écran.

![](../Attachements/assemblage_vis_import_x.jpg)

Dans le cas où  vous cliquez sur le **bouton z**, la pièce va so'rienter horizontalement à votre écran.

![](../Attachements/assemblage_vis_import_z.jpg)

Il y a aussi une possibilité de changer l'orientation du plan de l'espace de travail en cliquant sur l'une des flèches su système de coordonnées principales de SolidWorks, comme la figure suivante, dans mon cas j'ai cliqué sur la **flèche x**.

![](../Attachements/assemblage_vis_import_z_fx.jpg)

Pour savoir si votre pièce est fixée un signe (f) va précéder le nom de la pièce comme dans la figure suivante.

![](../Attachements/piece_fixee.jpg)

Vous pouvez répéter l'opération pour importer l'écrou, cette fois-ci la pièce est libre car son nom est précédé par (-).

![](../Attachements/assemblage_ecrou.jpg)

#### c. Enregister l'assemblge

Il faudra penser à enregistrer nos assemblages en fur et à mesure qu'on avancera dans nos projet, pour cela il faut tout cliquer sur le bouton "enregistrer " su menu Fichier. puis donner un nom à notre fichier d'assemblage.

![](../Attachements/enregister_assemblage.jpg)

Les fichiers d'assemblage sous SolidWorks ont l'extension **".sldasm"**.

#### d. Fonctions de bases sur les assemblages

###### 1- Origine pièce/environnement

L'une des notion les plus importante dans l'importation des pièces pour les assemblages et l'origine de la pièce et l'orgine de l'envoronement SolidWorks, il faut toujours les faire coincider.

Nous avions appris à importer les pièces, mais au moment de l'import il faut s'assurer de la coincidence des origines pièce/environnement, car ça va nous faciliter la tâche dans le future.

Si je reviens à mon exemple, de vis-écrou, on avait pas fait attention à faire correspondre l'origine de la pièce avec celle de SolidWorks, pour faire ça, il vous suffit seulement où moment de l'importation de cliquer sur le bouton de visibilité qui a une icone d'oeuil, et de choisir 

![](../Attachements/assemblage_origine_visib.jpg)

Le résultat sera que les deux origines vont apparaitre dans votre projet d'assemblage.

![](../Attachements/assemblage_origine_active.JPG)

Il ne vou reste que de faire pivoter votre pièce vers l'origine SolidWorks et de valider en liquant sur le bouton droit de la souris pour créer certe première contrainte.

![](../Attachements/assemblage_contrainte_origines.jpg) 

###### 2- Menu contextuel

Quand on clique sur le bouton droit de la souris, on aura un menu avec lequel il nous y est possible de faire beaucoup de choses : 

- Fixer / bouger ou libérer une pièce : avec cette fonctionnalité vous serez capable de fixer ou de faire translater vos pièces ;

- ###### 3- Assemblage sur place

Il existe un moyen de faire un assemblage sur place, cela veut dire qu'on peut se servir des fonctionnalités de conception dans un projet d'assemblage dans SolidWorks pour créer une pièce qui ne sera pas référencer de l'extérieur de projet comme on vient de le faire en haut.

Ces pièces ne seront visible que dans le projet d'assemblage. Pour cela on va utiliser la pièce "nouvelle_piece_3.sldprt", comme la figure suivante.

![](../Attachements/nouvelle_piece_3.jpg)

On va créer tout d'abord un projet d'assemblage, puis on va importer notre pièce, puis en cliquant sur le bouton __Insérer des composants__, puis sur __Nouvelle pièce__.

![](../Attachements/nouvelle_piece_3_n.jpg)

Vous allez vous rendre compte que SolidWorks avait crée une nouvelle piece sur l'arborescence, le circonflexe dans le nom de la pièce veut dire qu'il dépend du projet d'assemblage.

![](../Attachements/arbo_nouvelle_piece_3.jpg)

Pour continuer notre assemblage, on utilise les fonctions de conception, précisement *Convertir les entités*, pour cela on clique tout d'abord sur la partie dans laquelle on veut créer une nouvelle pièce, comme sur la figure suivante.

![](../Attachements/asseb_nouvelle_piece_3_selec.jpg)

Maintenant on séléctionne le contour du haut de notre pièce, et on appuis sur la fonction *Convertir les entités*.

![](../Attachements/asseb_nouvelle_piece_3_cont.jpg)

On passe maintenant la fonction *Bossage*, j'ai choisis 5 mm pour l'épaisseur, après il vous suffit seulement de valider.

![](../Attachements/asseb_nouvelle_piece_3_cont_bossage.jpg)

SolidWorks va  vous créer une contrainte automatiquement, un clic avec le bouton droit de votre souris puis sur __Editer la fonction__, SolidWorks va vous faire apparaitre un message d'avertissement, vous validez, vous aurez ensuite l'éditeur de propriété de la fonction, vous choisissez la contrainte coincidence, puis vous validez.

![](../Attachements/asseb_nouvelle_piece_3_coincidence.jpg)

Vous pouvez dès à présent supprimer cette contrainte après avoir valider l'avertissement de SolidWorks.

Maintenant vous pouvez faire bouger le couvercle de notre pièce.

![](../Attachements/asseb_nouvelle_piece_3_couvercle.jpg)

###### 4- Ouvrir une pièce dans un assemblage

Il est possible d'ouvrir une pièce même dans le cas d'un assemblage sur place sous SildWorks en mode édition (partie conception ) pour lui apprter des modifications.

Il vous suffit seulement de cliquer avec le bouton droit de votre souris sur la pièce dans l'arborescence puis de cliquer sur la fonction __Ouvrir la piece__.

![](../Attachements/asseb_nouvelle_piece_3_couv_edition.jpg)

SolidWorks va vous ouvrir la pièce en mode édition, pour utiliser toutes les fonctionnalités de conception. Je vais apporter quelques modifications,

![](../Attachements/asseb_nouvelle_piece_3_couv_conception.jpg)

Je continue avec __l'enlèvement de la matière__, puis j'enregistre mon travail quand je ferme la pièce,

![](../Attachements/asseb_nouvelle_piece_3_troues.jpg)

###### 5- Créer un sous-assemblage

Il est possible de créer autant de sous-assemblages qu'on veut sur SolidWorks, je vais 

![](../Attachements/asseb_nouvelle_piece_3_vis.jpg)

Pour pouvoir créer un sous-assemblage sous SolidWorks, soit vous cliquez sur __Nouvel assemblage__, de l'onglet *Assemblage*, 

![](../Attachements/asseb_nouvelle_piece_3_n_sous_assemb.jpg)

Maintenant vous aurez dans l'arborescence de création un nouvel assemblage, vous sélectionnez les quatres vis en vous servant du bouton __ctrl__ de votre clavier , puis vous les faites glisser avec en maintenant le clic droit de votre souris dans cet nouvel assemblage.

![](../Attachements/asseb_nouvelle_piece_3_glisser.jpg)

Maintenant quand vous cliquez sur le nouvel assemblage de l'arborescence SolidWorks vous met les quatres vis en couleur bleu.

![](../Attachements/asseb_nouvelle_piece_3_sous_assemb.JPG)

**Note** : Dans le cas où il vous ai impossible de faire ce que je viens de faire, il vous suffit de vous rendre dans le menu *Option*, puis dans l'onglet *Assemblage* et de cocher l'option *Enregistrer les nouveaux composants dans des fichiers externes*

![](../Attachements/assemb_option_enreg.JPG)

###### 5- Enregistrer les composants dans des fichiers externes

Il existe un moyen qui nous permettra comme même de sauver les composants qu'on peut créer dans un projet d'assemblage dans des fichiers externes.
