# Laravel e Vue Blog


## Tecnologias

### Frontend

* [VueJS](https://fr.vuejs.org/index.html) 
* [Bootstrap 4](https://getbootstrap.com)
* [Vuex](https://getbootstrap.com)

### Backend

* PHP 8
* SQLite3 para desenvolvimento e MySQL para producao.
* PHPUnit 
* [Laravel](http://www.laravel.com) 
* [Tymon/Jwt-auth](https://jwt-auth.readthedocs.io/en/develop/) 


Prerequisites
PHP 9
SQLite3
Git
Composer
Getting Started
Clone the project from Github

    $ git clone https://github.com/wesleylopesdias/DealersitesWesley.git
    $ cd DealersitesWesley
    DealersitesWesley$
Install the packages for laravel:

   DealersitesWesley$ composer install
Create the database:

    DealersitesWesley$ touch database/database.sqlite
Create the .env file :

    DealersitesWesley$ cp .env.example .env
Generate the encryption key for Laravel :

    DealersitesWesley$ php artisan key:generate
Add database information :

    DealersitesWesley$ vim .env
Change the DB_CONNECTION to put sqlite :

    DB_CONNECTION=sqlite        
Load sample records:

    DealersitesWesley$ php artisan migrate --seed
Run the Laravel Server in development mode

    DealersitesWesley$ php artisan serve
Start client in development mode. You should be able to go to http://localhost:8000

To access to the administration panel, there is a link in the bottom of the page or go to http://localhost:8000/login

