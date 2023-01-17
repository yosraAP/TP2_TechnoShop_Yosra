            *************************** PROGRAMMATION D'APPLICATIONS WEB ****************************
		*****************************************************************************************
            **********************		420-A11-BB  gr.01234		 ****************************
		*****************************************************************************************
		*****************	              Author : yosra houas                *********************
		
		
		#Titre du projet : Techno-Shop 
		***
         - Le site de E-Commerce permet de vendre du matériel électronique sur Internet.
		***
		
		***
		## Les etapes pour excecter le projet :
		***
		
		***
		### Executer Le script :
		***
		- Executer Le script pour la creation de base de données , Nous avons utilsé MySQL oracle
		- le fichier sql a executé nommé " Bd_Techno_Shop.sql " se trouve dans le dossier 'bd_Techno_Shop' .
		***
		***
		#### Changement pour le fichier web.xml
		***
		- dans le fichier web.xml il est nécessaire de changer le mot de passe avec votre propre que vous 
		sur MySQL Workbench.
		***
		
		***
		#####Les Pages Web du projet : ce projet comporte 12 pages jsp
		***
		
		***
		 1 .index : 
		 ***
		 - la page index permet à l'utilisateur de consulter tous les autres pages de projets
		 - Permets aux utilisateurs de faire l'internationalisation vers anglais, 
		 la langue principale c'est français.
		 ***
		 2 .listerProduct : 
		 ***
		 - pour accéder à tous les produits offerts sur notre site , l'utilisateur doit cliquer sur magasiner ou 
		 (shop : si le site est traduit en anglais).
		 ***
		 3 .listerProductDetail :
		 ***
		 - pour afficher le produit sur le détail cliquez simplement sur le nom se produit, cette action amène l'utilisateur 
		 à la page "listerProductDetail".
		 - À partir de la page produit en détail , l'utilisateur a l'accès pour ajouter ce produit au panier.
		 ***
		 4 .panier : 
		 ***
		 - si le panier avait au moins un produit, l'utilisateur est invité à effectuer la 
			- mis à jour de  quantité.
			- supprimer produit.
			- revenir à la page où l'on trouve tous les produits pour en ajouter d'autres.
		 5 .modifierPanier : La gestion du panier est effectuée depuis cette page.
		 ***
		 6 .Checkout: l'utilisateur doit ouvrir une session pour accéder à cette page et procéder au paiement.
		 ***
		 7 .login : cette page permet à l'utilisateur de se connecter.
		   - Si les coordonnées de connexion sont invalides, une page d'erreur s'affiche.
		   8 . pageErreur : Cette page figure dans le répertoire WEB-INF.
		 ***
		 9 .formulaireUser : cette page permet l'inscription sur notre site.
		 ***
		 10 .changerMotPass : l'utilisateur a la possibilité de modifier son mot de passe 
		 depuis cette page permet
		 ***
		 11 .contact : permet à l'utilisateur de nous contacter en cas de problème .
		 ***
		 12 .succesPage: lorsque le client clique sur le bouton pour payer une page de succès de paiement s'affiche.
		***
		

		
		
		 
						