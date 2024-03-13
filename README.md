<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></p>

<p align="center">
<a href="https://github.com/laravel/framework/actions"><img src="https://github.com/laravel/framework/workflows/tests/badge.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

## About Laravel

Laravel is a web application framework with expressive, elegant syntax. We believe development must be an enjoyable and creative experience to be truly fulfilling. Laravel takes the pain out of development by easing common tasks used in many web projects, such as:

- [Simple, fast routing engine](https://laravel.com/docs/routing).
- [Powerful dependency injection container](https://laravel.com/docs/container).
- Multiple back-ends for [session](https://laravel.com/docs/session) and [cache](https://laravel.com/docs/cache) storage.
- Expressive, intuitive [database ORM](https://laravel.com/docs/eloquent).
- Database agnostic [schema migrations](https://laravel.com/docs/migrations).
- [Robust background job processing](https://laravel.com/docs/queues).
- [Real-time event broadcasting](https://laravel.com/docs/broadcasting).

Laravel is accessible, powerful, and provides tools required for large, robust applications.

## Installation

1. Clone the repository
2. Run `composer install`
3. Run `npm install`
4. Run `npm run dev`
5. Create a new database and add the database credentials to the .env file
6. Run `php artisan migrate`
7. Run `php artisan serve`
8. Open the project in your browser and navigate to `http://localhost:8000`

> Note: You can also use the `php artisan serve` command to start a development server. You can also use Laravel Valet, Laravel Homestead, or Docker.

## Route List :

| Metode | Rute       | Controller                                  |
|--------|------------|---------------------------------------------|
| GET|HEAD | dashboard  | DashboardController                        |
| GET|HEAD | login      | Auth\LoginController@index                 |
| POST   | login      | Auth\LoginController@store                 |
| POST   | logout     | Auth\LoginController@destroy               |
| GET|HEAD | register   | Auth\RegisterController@index              |
| POST   | register   | Auth\RegisterController@store              |

## License

The Laravel framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
