# Le processus d'amorcage du noyau

Ce chapitre décrit le processus d'amorcage du noyau linux. Ici vous trouverez une série de posts qui expliquent en détail la façon dont le noyau se charge:
 
* [Du chargeur d'amorcage au noyau](linux-bootstrap-1.md) - décris toutes les étapes du démarrage de l'ordinateur jusqu'à la première instruction du noyau. 
* [Les premières étapes de configuration du noyau](linux-bootstrap-2.md) - décris les premières étapes de la configuration du noyau. Vous verrez ici l'initialisation du tas, la requête de différents paramètres tels que l'EDD, IST, etc...
* [Initialisation du mode vidéo et transition vers le mode protégé](linux-bootstrap-3.md) - décris l'initialisation du mode vidéo dans le code de configuration du noyau, et le passage en mode protégé.
* [Transition vers le 64-bits](linux-bootstrap-4.md) - décris la préparation pour le passage vers le 64-bits et les détails sur la transition.
* [La décompression du noyau](linux-bootstrap-5.md) - décris la préparation avant la décompression du noyau, ainsi que les détails sur cette décompression.
* [La distribution aléatoire de l'espace d'adressage du noyau (kASLR)](linux-bootstrap-6.md) - décris la distribution aléatoire de l'espace d'adressage du noyau Linux.

Ce chapitre a été écrit en se basant sur la version ``4.17`` du noyau Linux.
