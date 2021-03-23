# Developpement Collaboratif
**Le developpement collaboratif** désigne une organisation spécifique du travail de groupe sur un ensemble de fichier qui forment a priori un projet spécifique. 
On peut retrouver cette organisation sous diverses formes: procédures, outils, etc. Toutes s'employant à cadrer le travail de développement afin que le projet grandisse dans la bonne direction et que les actions de chacun ne nuisent pas au travail des autres.
Le but est donc de permettre à chacun de travailler de façon individuelle avant de mettre en commun le fruit de son travail afin que ses modifications soient diffusées aux autres. On peut ainsi éviter les pertes de données liées aux mises à jour successives et assurer la gestion des versions successives du projet.

>Parmis les outils du dev collaboratif: Les logiciels de gestion de versions (GIT est le plus connu) ou vcs
# Logiciel de gestion de version
Un vcs permet de sauvegarder une historique de tout les changements que le projet a subit et pouvoir ainsi revenir en arrière à chaque moment.
Les vcs permettent aussi d'appliquer les nouveau changements directement au dossier du projet (appellé dépôt ou répository) automatiquement ,sans avoir à télécharger l'ensemble des fichiers du projet et/ou rajouter les changements effectués par ses collègues manuellement. Il permettent donc non seulement de gérer le travaille en équipe mais aussi de faire un log exhaustive des changements et des différentes versions, et surtout de faciliter l'intégration des changement dans le projet directement (plus besoin de passer les fichiers par clé USB / service de partage de fichiers et les copier dans le dossier du projet manuellement et/ou rajouter des lignes de codes écrites par un collègue)
## VCS centralisé
l'historique du projet est stocké dans un serveur centrale , si on veut avoir la première version du fichier X on doit avoir une connexion avec le serveur pour le télécharger.
Si on veut changer quelque chose on télécharge la dernière version , on modifie et on envoie vers le vcs centralisé pour appliquer le changement.
## VCS distribué 
Chaque client possède son propre vcs autonome , et chaque projet donc est téléchargé avec la totalité de son historique.
Vous pouvez même télécharger ce projet , vous trouverez un dossier .git dedans contenant toute l'historique des modifications que vous pouvez visionner librement hors connexion. ( télécharger git kraken pour avoir une vue graphique de l'arbre des changements)
Chaque dépôt est autonome mais plusieurs copies du même dépôt peuvent être "synchronisé" , et ceci seulement en synchronisant leurs historiques (voir les commandes git pull , git push , git fetch ainsi que les notions du merging et remote repository pour en savoir plus)
# Git
Git est un logiciel de gestion de versions décentralisé. C'est un logiciel libre créé par Linus Torvalds, auteur du noyau Linux.
C'est donc un programme que vous pouvez télécharger et utiliser dans votre Pc. C'est un outil de commande donc utilisable avec CMD (commandes dans la diapo)
# GitHub
Permet de créer des repositories (ou dépôts) en ligne dans leur serveur. Il s'agit donc d'un Saas qui est très populaire dans le domaine de developpement collaboratif.
Vous pouvez trouver les repositories de plusieurs grands projets open source sur github, par exemple : 
 > React https://github.com/facebook/react
 > 
 > Laravel https://github.com/laravel/laravel
 > 
 > Django https://github.com/django/django 
 > 
 > Typescript https://github.com/microsoft/TypeScript

GitHub fournie plusieurs outils pour faciliter la collaboration massive dans les projets Open source, nottement l'option de Fork (vous pouvez l'essayer sur ce projet , ca créera une répository "clone" de celle ci sur laquel vous avez le droit d'édition, dans le but de la modifier et soumettre une pullRequest si vous voulez contribuer)
