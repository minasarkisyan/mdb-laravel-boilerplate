<div>
    <a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400"></a>
<picture>
 <source srcset="https://mdbootstrap.com/wp-content/themes/mdbootstrap4/content/en/_mdb5/standard/pro/_main/assets/mdb5-about-v2.webp" type="image/webp">
  <img src="https://mdbootstrap.com/wp-content/themes/mdbootstrap4/content/en/_mdb5/standard/pro/_main/assets/mdb5-about-v2.jpg" class="img-fluid shadow-5 rounded" alt="MDB 5 -    Bootstrap 5 &amp; Material Design 2.0" width="400">
</picture>
</div>

## mdb-laravel-boilerplate
Starting template for mdb and laravel
<ul>
    <li><a href="https://laravel.com" target="_blank">Laravel</a></li>
    <li><a href="https://mdbootstrap.com/docs/standard/" target="_blank">MDBootstrap</a></li>
</ul>

Laravel is accessible, powerful, and provides tools required for large, robust applications.
Bootstrap 5 & Material Design 2.0. Material Design for Bootstrap
The world's most popular framework for building responsive, mobile-first websites and apps

All this allows us to build anything with minimal development efforts. The application is ready for further construction for your tasks. From a simple blog to complex e-commerce projects. Thanks to ready-made components, we do not need to separately highlight the front-end developer, as well as spend time on adaptability for mobile devices.

While some may not like the material design style, this is a matter of taste.

## Installation

Please check the official laravel installation guide for server requirements before you start.

Clone the repository

git clone https://github.com/minasarkisyan/mdb-laravel-boilerplate.git
Switch to the repo folder

# cd mdb-laravel-boilerplate
Install all the dependencies using composer

# composer install
Copy the example env file and make the required configuration changes in the .env file

# cp .env.example .env
Generate a new application key

php artisan key:generate

php artisan jwt:generate
Run the database migrations (Set the database connection in .env before migrating)

php artisan migrate
Start the local development server

php artisan serve
You can now access the server at http://localhost:8000
## Laravel Sponsors

We would like to extend our thanks to the following sponsors for funding Laravel development. If you are interested in becoming a sponsor, please visit the Laravel [Patreon page](https://patreon.com/taylorotwell).

### Premium Partners

- **[Vehikl](https://vehikl.com/)**
- **[Tighten Co.](https://tighten.co)**
- **[Kirschbaum Development Group](https://kirschbaumdevelopment.com)**
- **[64 Robots](https://64robots.com)**
- **[Cubet Techno Labs](https://cubettech.com)**
- **[Cyber-Duck](https://cyber-duck.co.uk)**
- **[Many](https://www.many.co.uk)**
- **[Webdock, Fast VPS Hosting](https://www.webdock.io/en)**
- **[DevSquad](https://devsquad.com)**
- **[OP.GG](https://op.gg)**

## Contributing

Thank you for considering contributing to the Laravel framework! The contribution guide can be found in the [Laravel documentation](https://laravel.com/docs/contributions).

## Code of Conduct

In order to ensure that the Laravel community is welcoming to all, please review and abide by the [Code of Conduct](https://laravel.com/docs/contributions#code-of-conduct).

## Security Vulnerabilities

If you discover a security vulnerability within Laravel, please send an e-mail to Taylor Otwell via [taylor@laravel.com](mailto:taylor@laravel.com). All security vulnerabilities will be promptly addressed.

## License

The Laravel framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
