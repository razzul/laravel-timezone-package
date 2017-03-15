# laravel-timezone-package
Creating you first start-up package for laravel

> composer require razzul/timezones
> php artisan vendor:publish

add new Service Provider to the array of Service Providers in file config/app.php:
```php
'providers' => [

        /*
         * Laravel Framework Service Providers...
         */
        // ... other providers
        Razzul\Timezones\TimezonesServiceProvider::class,
```
