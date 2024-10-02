### Commandes de Base
## Navigation 

# Commande	Description

h, j, k, l	Déplacer le curseur à gauche, en bas, en haut, à droite
gg	Aller au début du fichier
G	Aller à la fin du fichier
0	Aller au début de la ligne
$	Aller à la fin de la ligne
w	Aller au début du mot suivant
b	Aller au début du mot précédent
e	Aller à la fin du mot actuel
Ctrl + u	Défilement vers le haut de la moitié de la page
Ctrl + d	Défilement vers le bas de la moitié de la page
Ctrl + f	Défilement vers le bas d'une page entière
Ctrl + b	Défilement vers le haut d'une page entière
---------------------------------------------------------------------------------
---------------------------------------------------------------------------------

---------------------------------------------------------------------------------
---------------------------------------------------------------------------------
###########################  Modes ##############################################
---------------------------------------------------------------------------------
---------------------------------------------------------------------------------
Commande	Description
i	Entrer en mode Insert avant le curseur
I	Entrer en mode Insert au début de la ligne
a	Entrer en mode Insert après le curseur
A	Entrer en mode Insert à la fin de la ligne
o	Insérer une nouvelle ligne en dessous et entrer en mode Insert
O	Insérer une nouvelle ligne au-dessus et entrer en mode Insert
v	Entrer en mode Visual
V	Entrer en mode Visual par ligne
Ctrl + v	Entrer en mode Visual en bloc
Esc	Retourner en mode Normal
-----------------------------------------------------------------------------------
-----------------------------------------------------------------------------------
############################  Édition #############################################
-----------------------------------------------------------------------------------
-----------------------------------------------------------------------------------
Commande	Description
x	Supprimer le caractère sous le curseur
X	Supprimer le caractère avant le curseur
dd	Supprimer la ligne actuelle
dw	Supprimer le mot actuel
d$	Supprimer du curseur à la fin de la ligne
d0	Supprimer du curseur au début de la ligne
D	Supprimer du curseur à la fin de la ligne
yy	Copier la ligne actuelle
yw	Copier le mot actuel
y$	Copier du curseur à la fin de la ligne
y0	Copier du curseur au début de la ligne
p	Coller après le curseur
P	Coller avant le curseur
u	Annuler la dernière action
Ctrl + r	Rétablir l'annulation
.	Répéter la dernière commande
r<car>	Remplacer le caractère sous le curseur par <car>
J	Joindre la ligne suivante à la ligne actuelle
:s/old/new	Remplacer la première occurrence de "old" par "new" sur la ligne courante
:s/old/new/g	Remplacer toutes les occurrences de "old" par "new" sur la ligne courante
:%s/old/new/g	Remplacer toutes les occurrences de "old" par "new" dans tout le fichier

--------------------------------------------------------------------------------------------------
--------------------------------------------------------------------------------------------------

######################### Sélection et Suppression ###############################################
--------------------------------------------------------------------------------------------------
--------------------------------------------------------------------------------------------------
Commande	Description
v	Entrer en mode Visual (sélection par caractère)
V	Entrer en mode Visual par ligne (sélection par ligne)
Ctrl + v	Entrer en mode Visual par bloc (sélection rectangulaire)
d	Supprimer la sélection
c	Changer la sélection (supprimer et entrer en mode Insert)
y	Copier la sélection
>	Augmenter le retrait de la sélection
<	Réduire le retrait de la sélection
----------------------------------------------------------------------------------------------------------------
----------------------------------------------------------------------------------------------------------------
############################ Insérer et Modifier du Texte ######################################################
----------------------------------------------------------------------------------------------------------------
----------------------------------------------------------------------------------------------------------------
Commande	Description
ciw	Changer le mot sous le curseur
caw	Changer tout le mot sous le curseur
ci"	Changer le texte entre guillemets
cib	Changer le texte entre parenthèses
diw	Supprimer le mot sous le curseur
daw	Supprimer tout le mot sous le curseur
di"	Supprimer le texte entre guillemets
dib	Supprimer le texte entre parenthèses
yiw	Copier le mot sous le curseur
yaw	Copier tout le mot sous le curseur
yi"	Copier le texte entre guillemets
yib	Copier le texte entre parenthèses
:r filename	Insérer le contenu du fichier filename ici
-------------------------------------------------------------------------------------------------------------------------
-------------------------------------------------------------------------------------------------------------------------
################################ Copier, Couper, et Coller ##############################################################
-------------------------------------------------------------------------------------------------------------------------
-------------------------------------------------------------------------------------------------------------------------
Commande	Description
yy	Copier la ligne actuelle
yw	Copier le mot actuel
y$	Copier du curseur à la fin de la ligne
y0	Copier du curseur au début de la ligne
p	Coller après le curseur
P	Coller avant le curseur
dd	Couper la ligne actuelle
dw	Couper le mot actuel
d$	Couper du curseur à la fin de la ligne
d0	Couper du curseur au début de la ligne
--------------------------------------------------------------------------------------------------------------------
--------------------------------------------------------------------------------------------------------------------
######################## Rechercher et Remplacer ###################################################################
--------------------------------------------------------------------------------------------------------------------
--------------------------------------------------------------------------------------------------------------------
Commande	Description
/mot	Rechercher "mot" dans le texte
?mot	Rechercher "mot" en arrière dans le texte
n	Aller à la prochaine occurrence du mot recherché
N	Aller à l'occurrence précédente du mot recherché
:%s/old/new/g	Remplacer toutes les occurrences de "old" par "new"
:%s/old/new/gc	Remplacer toutes les occurrences de "old" par "new" avec confirmation
:noh	Désactiver le surlignage de la recherche

---------------------------------------------------------------------------------------------------------------------
---------------------------------------------------------------------------------------------------------------------
################################  Gestion des Fichiers ##############################################################
---------------------------------------------------------------------------------------------------------------------
---------------------------------------------------------------------------------------------------------------------
Commande	Description
:w	Enregistrer le fichier actuel
:w filename	Enregistrer sous un nouveau nom
:q	Quitter Vim
:q!	Quitter sans enregistrer
:wq ou :x	Enregistrer et quitter
:e filename	Ouvrir un fichier
:enew	Ouvrir un nouveau fichier
:bnext ou :bn	Aller au prochain buffer
:bprev ou :bp	Aller au buffer précédent
:ls	Lister les buffers ouverts
:bd	Supprimer le buffer actuel
:r file	Lire le fichier file et insérer son contenu ici
------------------------------------------------------------------------------------------------------------------------------
------------------------------------------------------------------------------------------------------------------------------
#################################################### Onglets et Fenêtres #####################################################
------------------------------------------------------------------------------------------------------------------------------
------------------------------------------------------------------------------------------------------------------------------
Commande	Description
:tabe	Ouvrir un nouveau onglet
:tabc	Fermer l'onglet actuel
:tabn	Aller à l'onglet suivant
:tabp	Aller à l'onglet précédent
`:	








