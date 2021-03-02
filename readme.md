## Installation Steps:
- laravel new `<project_name>`
- composer require laravel/fortify
- `php artisan vendor:publish --provider="Laravel\Fortify\FortifyServiceProvider"`
- `php artisan migrate`
- Copy `auth` and `layouts` directory from `laravel/ui` and paste in `views` directory.
- Copy `css` and `js` directory from `public` directory from `laravel/ui` and paste in `public` directory.


### Additional Info:
- Register FortifyServiceProvider in providers array in `config/app.php` file.
- Add default views for auth in `FortifyServiceProvider.php` file.







## Reference:
- https://laravel.com/docs/8.x/fortify
- https://www.youtube.com/watch?v=NuGBzmHlINQ&ab_channel=LaravelDaily
