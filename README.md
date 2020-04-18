# crudly

## Installation

Get the code, for example:

```
$ git clone https://github.com/crudly/crudly.git
```

Copy `.env.example` to `.env`.

Get inside the project directory and install packages using [composer](https://getcomposer.org/):

```
composer update
```

Generate app key by executing this inside the project directory:

```
php artisan key:generate --ansi
```

Serve from the `public` directory using your web server or do this to make PHP serve it on `http://localhost:8000`:

```
php artisan serve
```
