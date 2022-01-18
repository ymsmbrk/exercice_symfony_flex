# exercice_symfony_flex
ATTENTION !
Toutes les commandes composer doivent êtres 
exécutés à la racine de votre projet 

Liens utiles :
https://symfony.com/doc/current/index.html
https://packagist.org

MODULE
(Symfony)
Symfony flex

Terminologie :
Trouver la définition des mots suivants :
 bundle 
“C’est tout simplement un paquet donc un ensemble de fichier”

 plugin
“Extension”

 module
“c’est le ou les composant ajouter via l’installation d’un plugin (donc d’une extension)”

Initié
charger quelque chose

repository
C’est un répertoire

Directory
C’est un dossier

ide
editeur de code

Exercice 1 :
initialisé un projet minimaliste nommée my_project_yourFirstname

Question :
Donnez la bonne syntaxe et expliquez l’utilité d’initié un projet minimaliste ?
Syntaxe :

symfony new project_symfony = composer create-project symfony/skeleton
//Permet de charger un projet minimaliste en spécifiant la version 
symfony new my_project_name --version=5.4

cette syntaxe permet de initialisé un projet minimaliste

Cela va permettre de réduire au minimum les dépendances liées au projet afin de le rendre le plus léger possible.
ce qui lui permettra une meilleure exécution.

Exercice 2 :
Une fois ce projet créer ajouter le plugin flex de symfony 

Question :
Donnez la bonne syntaxe ?
composer require symfony/flex

Exercice 3 :
Sur votre ide ouvrez le fichier composer.json et constater que le plugin et charger

Question :
Quel est l’utilité du composer.json ?
Le composeur.json et un référentiel des bundles que j’ai initialisé via composer require et qui sont nécessaire au projet

Exercice 4 :
Rendez-vous ensuite dans le repository config et ouvrir bundle.php sur votre ide,
constater qu’il n’y a qu’un seul bundle de charger avec le projet minimaliste

Question :
Combien de Bundle sont chargé(s) et quelle est l’utilité de ce fichier ?
1 bundle nécessaire pour faire fonctionner le projet minimaliste

 *Laisser votre reponse en commentaire dans le haut de ce fichier
“JE CONSTATE L’INITIATION MINIMALISTE ”

Exercice 5 :
Ajouté le bundle easy-admin et donner la bonne syntaxe
composer require easycorp/easyadmin-bundle

Question :
Toujours sur le fichier bundle.php ouvert sur votre ide,
constater le changement effectuer et décrivez le ?
A l’ajout du bundle easy admin, celui à initialiser les dépendances (bundle) nécessaire à son fonctionnement.

Synthèse :
Que peut-on dire de symfony/flex et de sont utilité ?

Symfony/flex permet d’ajouter directement les bundle spécifique à l’environnement de configuration de symfony ( voir: config/bundle.php )
Cela permet de se concentrer sur l’essentiel sans avoir à gérer ce processus manuellement.

This work is licensed under the Creative Commons Attribution - Pas d'Utilisation Commerciale - Pas de Modification 4.0 International License. To view a copy of this license, visit
http://creativecommons.org/licenses/by-nc-nd/4.0/.

