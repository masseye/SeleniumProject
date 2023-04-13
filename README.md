Ce petit projet d'apprentissage en Selenium a pour but de se familiariser aux elements de page web tels que les liens, boutons, tableaux, images, listes deroulantes... 
mais aussi a travailler avec des donnees excel. Il s'agira ici de tester un site de e-commerce selon deux (2) parties: inscription et achat d'un produit.

Scenario: Validation de la page d’inscription
Description : L’objectif de ce scenario n’est pas de vérifier la validité des donnes saisies mais plutôt de s’entrainer sur le chargement de données depuis un fichier Excel
Préconditions: 
•	L’application web est opérationnelle
•	L’utilisateur est sur la page d’accueil
Etapes
1.	Remplir le nom, le prénom et le sexe de l'utilisateur. Ces données sont chargées depuis un fichier Excel
2.	Soumettre le formulaire
3.	Vérifier l'affichage d'un message de succès
Post condition: un message de succès est affiché

Scenario: Achat d’un produit
Description : L’objectif de ce scenario est de tester l’achat d’un produit de bout en bout, de la recherche d’un produit à la confirmation de la commande.
Précondition: L’application web est opérationnelle
Etapes
1.	Cliquer sur l'onglet permettant d'accéder a la page des produits
2.	Rechercher un produit en particulier et l'ajouter à notre panier
3.	Confirmer la commande
4.	Préciser le lieu de livraison en testant l'autosuggestion de pays
5.	Vérifier l'affichage d'un message de succès
Post condition: un message de succès est affiché
