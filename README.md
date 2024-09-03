# Library_management_system

this project is Restfull API using Laravel for simple library management system that allow user to borrow book  exists in library .

## Features
-CRUD operation for basics in library (books , users, rating )
-Authintication and Authorization (only admin can create , read , update , delete [book,users] , and every authinticated user can borrow book from library and returned it )
-Any one can display available book in library and can filter it by author



##Setting up the project

1. Clone the repository 

2. nstall Dependencies: composer install 

3. edit .env file (DB_DATABASE=library)

4. Run Migrations To set up the database tables, run: php artisan migrate

3. start server (php artisan serve).

4. in file (Movie-Library-API.postman_collection) there are a collection of request to test api.




