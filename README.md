# Laravel Sportverse

## Requirements
PHP 8.3+
Laravel v12+
Livewire v3+
Filament v3

## Installation
- Clone git repository.
- Create a user

You can create a new user account with the following command:
```
php artisan make:filament-user
```
Open /admin in your web browser, sign in, and start building your app!

Not sure where to start? Review the [Getting Started guide](https://filamentphp.com/docs/3.x/panels/getting-started) to learn how to build a complete Filament admin panel.

## Cache
### Optimizing Filament for production
To optimize Filament for production, you should run the following command in your deployment script:
```
php artisan filament:optimize
```
This command will cache the Filament components and additionally the Blade icons, which can significantly improve the performance of your Filament panels. This command is a shorthand for the commands php artisan filament:cache-components and php artisan icons:cache.

To clear the caches at once, you can run:
```
php artisan filament:optimize-clear
```
Best detail [here](https://filamentphp.com/docs/3.x/panels/installation#improving-filament-panel-performance)