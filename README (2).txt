TP OUTIL FORMEL

NOM ET PRENOMS : ABOKON BANGA CHRIST CEPHAS
LICENCE 2B

Rapport du programme: Gestion d'un bâtiment sécurisé.

INTRODUCTION

Ce projet consiste à développer un système de contrôle d'accès pour un bâtiment sécurisé. L'objectif est de gérer l'accès en fonction de deux critères :
La validité d'une carte.
La saisie correcte d'un code.
Le système est capable de vérifier les entrées, d'afficher des messages d'erreur, de déclencher une alerte après trois échecs, et de se réinitialiser.

STRUCTURE DU PROGRAMME

1.Classe ControlAcces :

	*Contient la logique principale du système et gère les états.
	*Méthodes clés :
		-verifierCarte : vérifie si la carte est valide.
		-verifierCode : vérifie si le code est correct.
		-verifierAcces : affiche l'état actuel du système.
		-reinitialiser : réinitialise le système.
2.Classe Main :

	-Fournit une interface utilisateur avec un menu interactif.
	-Utilise les méthodes obtenirEntier et obtenirBoolean pour gérer les entrées utilisateur.

FONCTIONS DU PROGRAMME

*Vérification de la carte :

	-L'utilisateur insère une carte et indique si elle est valide ou non (valeur true ou false).
	-Si la carte est valide, le système passe à l'étape de vérification du code. Sinon, un message d'erreur s'affiche.

*Vérification du code :

	-L'utilisateur entre un code et précise s'il est correct (true) ou non (false).
	-Après 3 tentatives échouées, le système déclenche une alerte.

*Gestion des états :

	-Le programme utilise des états (ATTENTE, VERIFIERCARTE, VERIFIERCODE, ALERTE, ACCESACCORDE) pour suivre les étapes du processus.

*Réinitialisation :

-Le système peut être réinitialisé pour remettre tous les paramètres à zéro.

*Menu interactif :

Un menu permet à l'utilisateur de choisir les actions à effectuer.

CONCLUSION

Ce projet répond aux besoins d'un système de contrôle d'accès à un bâtiment. Il est fonctionnel, claire , limpide et même améliorable. Le système garantit la sécurité en limitant les tentatives et en déclenchant une alerte en cas de problème.



