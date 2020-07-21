# Larapassport

> A starter kit with passport api fully configured

## Info

-   For authenticating with **API** we use passport in various frameworks. In this repo we configured passport api so that anyone could clone it and use it without doing the initial setups. This could save some time.

## Usage

-   clone the repo
-   delete the `.git` folder for your personal use.
-   Run `composer install`
-   configure `.env` with DB credentials.
-   generate php private key by `php artisan key:generate`
-   install passport by `php artisan passport:install`
-   run the site using `php artisan serve`
-   to check the routes please run `php artisan route:list`
