Make some notes about this process in MyNotes

Since we didn't specify a username in our docker-compose.yml file the database username is "postgres" and the password is "secret"

* If you run this command while the container is running you will be inside the apache server
    * docker-compose exec php-apache /bin/bash
        * you will be logged in as root and the terminal will show 
            * root@55b8e01a3291:/var/www/configuration-finder#
        