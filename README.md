# Laravel and Angular Single Page Comment App

This is the repository for the [scotch.io tutorial](http://scotch.io/tutorials/php/create-a-laravel-and-angular-single-page-comment-application).

## Installation

1. Clone the repo: `git clone git@github.com:scotch-io/laravel-angular-comment-app`
2. Install Laravel: `composer install --prefer-dist`
3. Change your database settings in `app/config/database.php`
4. If applicable, add your chosen database to php.ini to ensure PDO errors don't happen in the next step.
  - If using SQLite, you will need to run 'apt-get install php5-sqlite'
5. Migrate your database: `php artisan migrate`
6. Seed your database: `php artisan db:seed`
7. View your application in browser.
