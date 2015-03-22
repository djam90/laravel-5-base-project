# Laravel 5 Base Project

This repository aims to speed up the setup process when starting a new Laravel 5 project. It is quite opinionated but it works for me.

##Packages Included
- [Laravel 5 IDE Helper Generator]
- [Laravel Debugbar]
- [Laravel 5 Extended Generators]

##Installation
1. Download the repository as a zip file
2. Extract the contents into the desired location
3. Open a command line window in this directory
4. Run `composer install` which will install all packages, and also create the IDE helper for use in PHPStorm
5. Begin your project



##Optional Extras


#####To publish the IDE Helper config file, please run:

```
php artisan vendor:publish --provider=barryvdh/laravel-ide-helper --tag=config
```


[Laravel 5 IDE Helper Generator]:https://github.com/barryvdh/laravel-ide-helper
[Laravel Debugbar]:https://github.com/barryvdh/laravel-debugbar
[Laravel 5 Extended Generators]:https://github.com/laracasts/Laravel-5-Generators-Extended