# Projet_4
Développez-un-back-end-pour-un-client

INSTALLATION DU PROJET AVEC SYMFONY 4

Ci-dessous une documentation complète de l’installation du projet Back-end du musée du Louvre : les outils utilisés, la méthode utilisée. 

1-	INSTALLATION DES OUTILS AVEC POWESHELL

J’ai commencé par installer les outils suivants :
-	 Composer (gestionnaire de dépendances de PHP)
-	PHP 7.2.4 et MYSQL via WAMPSERVER 3.1.3
-	Le gestionnaire de versions GIT (pour la gestion de version d’évolution de mes fichiers).
Après installation j’ai testé les configurations Git, PHP (php -v), COMPOSER (composer -V).

2-	INSTALLATION DU PROJET

En exécutant la ligne de commande ci-dessous sur poweshell

-	composer create-project symfony/website-skeleton musseelouvre
Cela va me créer un nouveau projet (musseelouvre), télécharger et générer les dépendances, les répertoires et les dossiers de base dont j’ai besoin pour commencer.

3-	LANCER L’APPLICATION SUR SYMFONY 

Etant en mode dev il est pratique d’utiliser le serveur web PHP de Symfony.
-	Je commence par accéder à mon projet

cd musseelouvre
-	php bin/console server :run (pour le lancer le server PHP Symfony)   
-	http://localhost:8000/ pour lancer l’application sur un navigateur.

