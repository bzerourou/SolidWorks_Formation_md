$$version 1.1$$
Dans cette deuxième section on va commencer à assembler des petits systèmes en créant des contraintes entre les faces(frontières) de nos pièces afin de les bien assembler.

# Sommaire

## II. Contraindre des pièces

#### 1. Introduction aux contraintes

Une contrainte nous sert à lier deux pièces. nous l'avions déjà vu sur la partie création d'esquisse. Cependant, pour les assemblages, leur nombre est plus important.

Reprenons notre exemple de vis-écrou, après importation bien sur, pour contraindre ces deux pièces, cliquer sur le bouton de la fonction "Contrainte".

Maintenant il faut sélectionner le cylindre intérieur de l'écrou comme la figure.

![[contrainte_cylindre_int_ecrou.jpg]]

Après il faudra encore sélectionner cette fois-ci la partie extérieure de notre vis, vous allez voir que SolidWorks a automatiquement détecter la contrainte de type coaxiale entre les deux parties des de nos deux pièces, comme la figure suivante.

![[contrainte_vis_ecrou.jpg]]

Il ne vous reste que de valider la fonction. La contrainte est visible sur l'arbre de création.

![[contrainte_ecrou_rotation.jpg]]

Vous puvez constaté que mon écrou est libre en rotation et en translation suivant la hauteur de la vis (axe y), mais vous ne pouvez pas le faire bouger.


On va rajouter une deuxième contrainte, cette fois-ci de distance pour que mon écrou ne bouge plus suivant l'axe y.
Je recommence les opérations précédentes, je sélectionne la face basse de la tête de ma vis et la face haute de mon écrou, SolidWorks me proposera une contrainte de coïncidence, mais on va cliquer sur le bouton de la contrainte distance entourée en rouge et on valide (figure suivante).

![[contrainte_hauteur.jpg]]

Maintenant vous pouvez constaté que l'écrou ne bouge pas sur la hauteur, il peut seulement tourner . Pour le contraindre totalement on va rajouter une troisième contrainte. 
D'abord on recommence les mêmes opérations, cette fois-ci on sélectionne la face droite ainsi que l'une des six face extérieures de notre écrou, SolidWorks va vous proposer une contrainte parallèle entre ces deux faces.

![[contrainte_parallele.jpg]]

Maintenant nos deux pièces sont totalement contraintes.


$$version 1.2$$
#### 2. Liste des contraintes utilisées 

Il existe sur SolidWorks bien d'autres contraintes que les trois que nous venons de voir. Nous pourrions les regrouper sous trois grandes catégories : 

#### a. Contraintes standard

Nous allons voir dans cette première partie d'autres contraintes les plus utilisées sur SolidWorks.

##### 1. Coïncidente
C'est quand on veut nos deux faces se collent l'une contre l'autre.


##### 2. Perpendiculaire

Les deux faces seront perpendiculaires.


##### 3. Tangente

On l'utilise souvent avec entre les faces cylindriques et un plan, une face. 

##### 4. Bloquante 

Les deux entités sélectionnés seront bloqués entre eux, mais leurs mouvements seront liés, si on fait bouger une l'autre bouge aussi.

##### 5. Angle 

Cette contrainte permet de spécifier un angle entre deux entités sélectionnées.

#### b. Contraintes avancées 

##### 1. Symétrie
La contrainte de symétrie permet à deux entités de se comporter de façon symétrique par rapport à un plan.


###### 2. Glissière 

Une contrainte  glissière permet à un objet de glisser suivant une seule direction, les deux autres sont bloquées. Donc elle bouge avec une distance égale.

#### c. Contraintes mécaniques 

Les contraintes mécaniques sont vraiment spécifiques aux études des macanismes. 

Nous pourrions avoir : 
- Pivot; 
- Came; 
- Pignon-crémaillère; 
- engrenage droit; 
- engrenage hélicoïdale; 
- Cardan.
