# Simple Laravel Boilerplate Project

## Table of Contents

- [System Requirements](#system-requirements)
- [Dev Packages](#dev-packages)
- [Installation](#installation)
- [Docker](#docker)
- [License](#license)

## System Requirements

To be able to run Laravel Boilerplate you have to meet the following requirements:
- PHP >= 8.0.2
- PHP Extensions: BCMath, Ctype, Fileinfo, JSON, Mbstring, OpenSSL, PDO, Tokenizer, XML, cURL, Mcrypt, GD
- Node.js >= 8.x
- Composer >= 1.9.x

## Dev packages

- [Laravel Debugbar](https://github.com/barryvdh/laravel-debugbar)
- [Laravel IDE Helper Generator](https://github.com/barryvdh/laravel-ide-helper)
- [Opinionated Laravel stubs](https://github.com/spatie/laravel-stubs)

## Installation

1. Clone repository
```
$ git clone https://github.com/jwebas/laravel-boilerplate.git
```

2. Change into the working directory
```
$ cd laravel-boilerplate
```

3. Copy `.env.example` to `.env` and modify according to your environment
```
$ cp .env.example .env
```

4. Install composer dependencies
```
$ composer install --prefer-dist
```

5. Build and run sail
```
$ vendor/bin/sail build && vendor/bin/sail up -d
```

6. An application key can be generated with the command
```
$ vendor/bin/sail artisan key:generate
```

## Docker

- PhpMyAdmin: [http://localhost:8080](http://localhost:8080)

## License

The Laravel framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
