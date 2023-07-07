# Environnement de développement Web avec PHP & MySQL

Je vous partage ici le fichier **_`php-stack.tar.gz`_** qui permet de créer une Pile Serveur "_contenarisée_" équivalente à LAMP (_Linux Apache MySQL et PHP_)

Une fois extrait vous trouverez dans ce dossier le fichier **_`docker-compose.yml`_** et un fichier caché nommé "**_`.env`_**" qui contient les variable d'environnement du SGDBR dont voici ci-dessous les informations (_de connexion_) : <br><br>

```
MYSQL_ROOT_PASSWORD=mot2passeRoot
MYSQL_DATABASE=myapp
MYSQL_USER=monutilisateur
MYSQL_PASSWORD=mot2passUser
```
<br>

## Prérequis
- Installer "Docker" sur votre machine
- Décompresser et extraire le fichier TAR que vous venez de rappatrier
- Renommez le dossier **"`php-stack`"** au nom de votre projet (_éviter les espaces dans le nom du dossier_)
  - Créer les sous-dossiers **"`app`"** et **"`db`"** dans votre dossier projet
- Le fichier _`docker-compose.yml`_ doit être au même niveau que vos dossiers _`app`_ et _`db`_<br><br>

## Accès au site web et/ou à la base des données
- Pour accéder au site web avec un navigateur internet, il faut taper dans la barre d'adresses [localhost](http://localhost)
- Pour accéder à la base de données avec PHP-MyAdmin via un navigateur web, il faut taper l'adresse [localhost:8080](http://localhost:8080)

J'espère que cette "_stack_" vous sera utile.
