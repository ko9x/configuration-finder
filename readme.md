* Make some notes about this process in MyNotes!

* To spin up the docker container navigate to the root directory of this project in terminal and run this command:
    * `docker-compose up -d`
* To shut down the docker container navigate to the root directory of this project in terminal and run this command:
    * `docker-compose down`

* Since we didn't specify a username in our docker-compose.yml file the database username is "postgres" and the password is "secret"

* If you run this command while the container is running you will be inside the apache server
    * docker-compose exec php-apache /bin/bash
        * you will be logged in as root and the terminal will show 
            * root@55b8e01a3291:/var/www/configuration-finder#
        