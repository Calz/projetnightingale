projetnighYNgale
================

projet nightingale


La dernière version de nos travaux est en telechargement dans la sections download.


Explication du code:

Dans le fichier Main.js

Creation de la table tabledebutfin qui stocke le nom du morceaux de musique, du moment de debut et de fin.

creation d'une fonction qui se declenche et lors du changement de musique
La fonction vas chercher dans la table tabledebutfin si le morceau à été parametré si oui elle modifie les parametres pour
qu'il demarre à la position souhaité.( nous n'arrivons pas pour le moment à definir la fin du morceau, Il n'y'a pas de parametre
qui definisse la fin seulement un parametre qui definie la duré en octet .cb d'octet pour un seconde ??)
Peut être faut il creer un thread (Est ce faisable) pour lire la position du lecteur et changer de morceau lorsqu'il a dépassé celle de fin...


Dans le fichier fenetre.xul
C'est la fenetre qui permet de saisir les parametres du morceau:
Il faut que prealablement le morceau soit selectionné puis on vas dans outil-> doHelloWorld et on saisie un temps de début et de fin.


Fichier début .js
La fonction dans ce fichier ce déclenche après la saisie de données. ELle permet l'insertion des informations saisies dans la base de donnée






