Base de données Topographiques du sytème karstique du massif de Bange (Massif des Bauges, Savoie, 73, France)
===============================================================================================

Overview
--------

Ce dépôt est mis à jour à chaque fois qu'une nouvelle topographie est rajoutée au système décrit dans cette base de données.

Description
-----------

Ce dépôt sauvegarde les données topographiques et de dessin. Ces fichiers sont pour le logiciel Therion (data + dessins).

Uniquement les fichiers sources sont sauvegardés pour des raisons de taille
	
	* .thc, .th, .th2 et .thconfig pour le logiciel Therion
    * .zip pour les exports des séances de l'appli Topodroid
	
Pour obtenir les topographies en plan, coupe et/ou 3D, il faut compiler les fichiers Therion, bien que certains exports de pdf soient présents à des fin de travail.


Une convention a été mise en place pour la gestion des points d'interrogation, avec la définition de différents champs.
S'utilise de la façon suivante, pour le point "Continuation" : 
    
    -attr Code "" -attr cavite "" -attr Reseau "" -attr CA "" -text ""

	* le champ "Code" qui décrit le type de terminus. Il peut prendre les valeurs : 
	
		* A : il suffit d'y aller et de continuer, pas d'obstacles
		
		* D1 : Désobstruction de petite ampleur, 

        * D2 : Désobstruction de moyenne ampleur,
		
		* E : Escalade nécessaire, 
		
		* P : Puits non descendu,
		
		* Q : non renseigné sur la topographie, c'est à voir/vérifier,
		
		* S : Siphon à plonger, 
		
		* T : Trémie à désobstruer
	
	* le champ "Cavite" qui donne le nom de la cavité en question,
	
	* le champ "Reseau" qui indique la partie de la cavité où se situe le point d'interrogation (pour pouvoir le retrouver plus rapidement sur les topographies),
	
	* le champ "CA" qui est rempli si présence de courant d'air, avec éventuellement des remarques/commentaires. Il est facultatif.

Licence
-------

L'ensemble de ces données est publié sous la licence libre Creative Commons Attribution-ShareAlike-NonCommercial (Attribution, partage à l'identique et non commerciale) :
	http://creativecommons.org/licenses/by-nc-sa/4.0/
