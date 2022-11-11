# GestiondeStock
Full Stack application developped by me using Springboot and Angular.
Application cloud : Le client n'a pas besoin de l'installer dans sa machine locale
                    il a besoin seulement d'une connexion internet et un navigateur web
  Plan de travail:
1-Conception(UML)
2-Creer un projet SpringBoot
3-Configurer le projet
4-Creer les entités, services...
5-Configurer Swagger(Api Documentation)
6-Generer le swagger.json => Generer les services, modeles de l'application front

  Frontend:
1-Decouper l'application en components
2-Creer les components
3-Creer les services
4-Developper les interfaces

  DevOps:
Role: Deploiement du code dans un serveur
      Fournir des outils aux développeurs pour travailler efficacement
      Améliorer la stabilité et la vitesse de production
1-Creer des images Docker (BDD,Backend(api))
2-Faire fonctionner l'application en dehors des IDE

  Cahier de charge:
On souhaite developper une application de gestion de stock pour répondre aux besoins de nos
clients.
Cette application permet de:
-Creer des profils pour chaque entreprise.
-Une entreprise a un ou plusieurs utilisateurs
-Parametrer les categories d'articles
-Une entreprise a un ou plusieurs articles/produits
-Une entreprise a un ou plusieurs Clients/Fournisseurs...
-Passer des commandes clients
  -Une commande client a un seul client
  -Une commande client a un ou plusieurs articles
  -Une commande client effectue une sortie de stock pour l'article en
   question
-Passer des commandes fournisseurs
  -Une commande fournisseur a un seul fourniseeur
  -Une commande fournisseur a un ou plusieurs articles
  -Une commande fournisseur effectue une entrée de stock pour l'article en
   question
-Effectuer des ventes au magasin 
  -Une vente a un ou plusieurs articles
  -Une vente effectue une sortie de stock pour les articles en question
-Consulter l'etat du stock de chaque article
  -Voir la qté de stock de l'article en temps réel
  -Effectuer des corrections de stock (mettre à jour le stock)
-L'application doit pouvoir envoyer automatiquement des emails aux fournisseurs lors de la
création d'une nouvelle commande fournisseur en se basant sur une template pré-definit
-L'application doit pouvoir envoyer un email de confirmation aux clients lors de la 
création de la commande client en utilisant une template pré-definit
-L'application doit afficher une notification lorsque un article atteint un seuil
minimale de stock.
-L'application doit avoir un tableau qui affiche les statistiques à definir :
  statistiques de ventes,...
-L'application offre une console d'administration pour les entreprises pour gerer des
utilisateurs, paramétrage.
-L'application offre un historique des commandes d'un client/fournisseur
-L'application offre une fonctionnalité de recherche par module (client,article,...)et un 
etat d'avancement des commandes.
-Lapplication doit etre sécurisé avec un systeme d'authentification











