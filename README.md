#La bibliothèque

**Disclaimer**: _Ce sont les consignes du cours de programmation web côté serveur de deuxième année. Certains points concernant des fonctionnalités d'interface peuvent n'avoir aucun effet particulier sur l'architecture de votre base de données._

##Objet
Ce projet vise à consolider votre apprentissage du développement d’une application côté serveur. Il utilise une base de données et le code doit être organisé selon une architecture formelle dérivée de MVC.

L’application résultante doit être un outil de gestion d’une bibliothèque.

##Fonctionnalités
Le site doit permettre à un visiteur anonyme de consulter le contenu de la bibliothèque en utilisant les critères de son choix parmi la liste suivante : titre d’un livre ; nom d’un auteur ; genre ; éditeur et emplacement dans la bibliothèque.

Par ailleurs, un utilisateur identifié doit avoir la possibilité d’ajouter, modifier ou supprimer les contenus présents dans la base de données.

La présentation des contenus doit être paginée. Ça me semble aller de soi, mais les projets observés les années précédentes manquaient systématiquement de cette fonctionnalité évidente, je préfère donc le préciser.

La fiche d’un livre doit présenter toutes les informations qui le concernent (voir un schéma possible de la base de données, nommé diagramme.png). Ces informations seront pour la plupart cliquables et déclencheront l’affichage des livres liés à l’information cliquée. Par exemple, cliquer sur le nom de l’éditeur d’un livre provoque l’affichage de la liste des livres que cet éditeur a publié en plus des infos générales relatives à l’éditeur bien sûr.

Il va de soi que les formulaires d’administration devront permettre une édition sécurisée de la base de données et que les règles d’ergonomie en matière de conception d’interactions devront être à l’œuvre avec notamment, l’affichage de feedbacks et de message informatifs.

L’utilisation de Javascript *n’est pas conseillée* dans ce projet, même s’il ne fait aucun doute qu’elle apporterait beaucoup. Nous la réserverons à une évolution du projet dans une transposition sur le framework Laravel à réaliser en troisième année.

De nombreuses fonctionnalités peuvent être ajoutées et vous êtes vivement encouragés à le faire. Par exemple, prévoir de commenter des livres, de les noter, permettre à un nouvel utilisateur de se créer un compte et donc gérer sa bibliothèque à lui (tout en veillant à ne pas créer de redondance dans la base de données. Si un livre existe déjà, on doit pouvoir éviter son encodage à l’utilisateur et réutiliser celui-ci), etc.
