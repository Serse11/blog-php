# BLOG EN PHP NATIVE

Le but de l'exercice est de mettre en place une structure d'application respectant le disgnPattern MVC  via un blog. Nous allons mettre en place :
    - un router permattant de gérer les pages via les URL
    - une authentification permettant aux utilisateur de se connecter
    - CRUD d'article permattant de gérer les données
    - une gestion de formulaire 
## ETAPE 1 : ROUTER

Nous allons commencer notre projet par la mise en place du router. Le router permet d'éxecuter le contrôleur lié à une URL, pour renvoyer la vue/template demandé par le client.

### Indication : 
    - Un router se compose

### Consignes

- Créer un répertoire nommé "blog_php"
- Dans le répertoire "blog_php", créer les répertoires et fichiers selon le shéma :
    -> /lib ***répertoire contenant les fonctionnalités de base de l'application***
        -> /controller
            ->Controller.php
        -> /repository
    -> /public ***porte d'entré de l'application ***
        -> index.php
    -> /src *** répertoire contenant la partie logique de l'application***
        -> /Controller
        -> /Model
        -> /service
            -> router.php
    -> /template *** répertoire contenant les vues de l'application ***
        -> /template_part
        -> base.php
- Dans /public/index.php
- Dans /src/service/router.php, créer un tableau nommé "routes" qui associe une 

