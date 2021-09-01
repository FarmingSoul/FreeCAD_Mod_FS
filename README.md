## FreeCAD_Mod_FS

 combinaison de module modifiés pour satisfaire attente de l'auto-construction
 
## FreeCAD Mod FS  v0.002

Pour suivre les balbutiement de FarmingSoul vers une utilisation
de FreeCAD compatible avec le fonctionnement de 
la Coopérative L’Atelier Paysan et potentiellement d'autres structures
tournées vers l'auto-construction et l'open source peuvent voir un intérêt 
à travailler leurs 3D et leurs plans avec un logiciel open-source.

# Pour l’instant ce Mod consiste à :

* Installation des modules d’assemblage AS2+ et Asm4 modifiés pour produire 
des nomenclature propre à L’Atelier Paysan.

![3](https://user-images.githubusercontent.com/65253765/130835216-29987c76-2f5a-47b1-83c9-8f3e9075a952.png)
![4](https://user-images.githubusercontent.com/65253765/130835219-86b8f53d-ecbf-43d7-9286-f1f40c797d03.png)
![5](https://user-images.githubusercontent.com/65253765/130835222-4471874c-b6da-4376-9712-925f45ad746c.png)

Ci dessous 2 exemple de profilés pour lesquels le button info par default fonctionne sur Asm4 et le macro automatique sur AS2+

vous devez seulement avoir des contraintes nomées ainsi dans sketcher :
-hauteur
-largeur
-epaisseur
-diametre
-conge

* "info par default" trouve le bon profilés pour ces configuration :
 * "fer rond" + diametre pour juste la constrainte diametre 
 * "fer plat" + largeur + X + hauteur pour les contraintes largeur, epaisseur, conge
 * "étiré plat" + largeur + X + hauteur pour les contraintes largeur, epaisseur
 * "tube rond" + diametre + X + epaisseur pour les contraintes diametre, epaisseur
 * "tube carré " + largeur + X + epaisseur pour les contraintes largeur, hauteur, epaisseur (for largeur = hauteur)
 * "tube rectangulaire" + largeur + X + hauteur + X + epaisseur pour les contraintes largeur , hauteur, epaisseur ( without largeur = hauteur )

Tube carré 25 X 2
![6](https://user-images.githubusercontent.com/65253765/130835223-c2adfe25-642a-4e79-af4d-c3c30bacd170.png)

Tube rond 30 X 2
![7](https://user-images.githubusercontent.com/65253765/130835224-5e5a96b1-a0a1-498f-b5e1-25494682b05c.png)

* Installation du module FastenersWB pour ce qui est de la boulonnerie.

* Installation du ‘Template’ actuellement utilisé pour les plans 
sortie de FarmingSoul.
Il vous sera utile pour ouvrir les plans conçu par FarmingSoul et
vous pouvez aussi le copier et le personnalisé pour votre utilisation .
Il est une rapide copie du fond de plan de L’Atelier Paysan .
PS : il vous est conseillez de le mettre en ‘Template’ par défaut 
( FreeCAD->Edition->Préférence->TechDraw->Template par défaut )
* Copie des Macro utilisé et peu être des test en cours
PS : vous devez les placer dans votre dossier actuelle de Macro ou
indiquer a FreeCAD que maintenant ce sera celui ci
(FreeCAD->Edition->Préférence->Général->Macro->Chemin de la macro)

# Installation :

* Ouvrez le dossier ‘FreeCAD_0.19xxx’ ou ‘FreeCAD_0.20xxx’
* Déplacer les 3 dossiers (data-macro-Mod) dans votre dossier racine de FreeCAD
* PS : il vous est conseillez de le mettre en ‘Template’ par défaut 
( FreeCAD->Edition->Préférence->TechDraw->Template par défaut )
* PS : vous devez les placer dans votre dossier actuelle de Macro ou
indiquer a FreeCAD que maintenant ce sera celui ci
(FreeCAD->Edition->Préférence->Général->Macro->Chemin de la macro)

# Installation fini !


*****************************************************************************
Il n’y a pour l’instant aucune doc d’utilisation elles viendront à la suite .
Vous pouvez néanmoins commencer à expérimenter .

# Amusez vous bien !
*****************************************************************************

Et pour la moindre question n’hésitez pas : 

# contact@farmingsoul.org 
                   
