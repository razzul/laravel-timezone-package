# laravel-timezone-package
Creating you first start-up package for laravel

> composer require razzul/timezones

add new Service Provider to the array of Service Providers in file config/app.php:
```php
'providers' => [

        /*
         * Laravel Framework Service Providers...
         */
        // ... other providers
        Razzul\Timezones\TimezonesServiceProvider::class,
```
> php artisan vendor:publish
