# docker-amp
- Création d'un docker du type AMP : Apache, MariaDB et PHP8 à parir du site :
https://www.bornfight.com/blog/blog-lamp-docker-setup-with-php-8-and-mariadb-for-symfony-projects/

- Le projet s'installe directement dans **codebase/**, attention dans la conf de apache il faut modifier le fichier :

> docker/server/apache/sites-enabled/site.conf 

pour pointer vers le dossier public de votre projet, ici il faut modifier le répertoire : 

> /var/www/html/my_project_directory/public