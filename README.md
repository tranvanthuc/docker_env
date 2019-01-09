**How to run docker with any project laravel**

* COPY `.env.example` to `.env`
* Change `PROJECT_PATH=path_your_project`
* Run `docker-compose up -d` 
* You can access to bash `docker exec -it docker_app bash`
* Run `composer install && php artisan config:cache`

**Thank you for watching**