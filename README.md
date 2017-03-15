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
        Illuminate\Foundation\Providers\ArtisanServiceProvider::class,
        // ... other providers
        Illuminate\View\ViewServiceProvider::class,
        Laraveldaily\Timezones\TimezonesServiceProvider::class,
```
