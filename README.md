Ping CRM
A demo application to illustrate how Inertia.js works.

![image](https://github.com/megatex123/Project007/assets/147833559/730e18c6-c26f-4b3f-b497-87508ed0d7a0)

Installation
Clone the repo locally:

git clone https://github.com/inertiajs/pingcrm.git pingcrm
cd pingcrm
Install PHP dependencies:

composer install
Install NPM dependencies:

npm ci
Build assets:

npm run dev
Setup configuration:

cp .env.example .env
Generate application key:

php artisan key:generate
Create an SQLite database. You can also use another database (MySQL, Postgres), simply update your configuration accordingly.

touch database/database.sqlite
Run database migrations:

php artisan migrate
Run database seeder:

php artisan db:seed
Run the dev server (the output will give the address):

php artisan serve
You're ready to go! Visit Ping CRM in your browser, and login with:

Username: johndoe@example.com
Password: secret
Running tests

To run the Ping CRM tests, run:
phpunit
