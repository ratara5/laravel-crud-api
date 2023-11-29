- Install Composer https://getcomposer.org/download/
- Init Laravel project: composer create-project laravel/laravel app-name https://laravel.com/docs/10.x/installation
. docker-compose up -d db
. Create connection in Tableplus
. docker-compose build
. IN NEW TERMINAL <TERMINAL1> docker exec -it db psql -U postgres
. IN NEW TERMINAL <TERMINAL2> docker exec laravelapp php artisan migrate
. IN <TERMINAL1> \dt
. IN <TERMINAL1> SELECT * FROM players;
. Use PPOSTMAN or similar software


TO STOP A CONTAINER: Ctrl+C
TO REMOVE A CONTAINER: docker-compose down -v
TO REBUILD A SERVICE: docker-compose up --build <nameservice> [Remember re-up server if is neccesary]
https://www.youtube.com/watch?v=cdlHJeHVFW4
