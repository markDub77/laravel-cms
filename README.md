# Laravel CMS with auth

## Valet
https://laravel.com/docs/8.x/valet


`laravel new cms`

`php artisan migrate`

`composer require laravel/breeze --dev`

`php artisan breeze:install`

`npm install && npm run dev`

`php artisan migrate`

`php artisan route:list`


Make the post model. The -m flag makes the migration for you

`php artisan make:model post -m`

Make the category model. The -m flag makes the migration for you

`php artisan make:model category -m`

Manually add custom tables like

$table->string('title');

$table->string('description');