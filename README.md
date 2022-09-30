# run laravel project(online celebration) using docker
#### Put the online celebration project in the src folder and it will be next to the docker-compose.yml file
#### run <code>docker-compose run composer update</code> with the utility containers prepared in the docker-compose.yml file
#### <code>docker-compose up server -d --build</code> to run nginx server which is based on php, mysql and phpmyadmin containers
#### run <code>docker-compose run artisan migrate</code> after running docker-compose up to prepare the database
#### run <code>docker-compose run artisan link:storage</code>
#### Edit the links on the index.blade.php page 