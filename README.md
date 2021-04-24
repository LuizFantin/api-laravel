# Laravel API using Sanctum

This is a repo that's implements a API authentication using Sanctum.

## First steps

Create a `.env` file based in `.env.example` and set your database credentials.

After, run this follow commands:

```composer
composer update
```

```composer
php artisan key:generate
```

```composer
php artisan migrate
```

## Usage

```composer
php artisan serve
```

Now, you will have the registration, login and show auth user routes.

#### Register: /api/register
#### Login: /api/login
#### Show Auth User: /api/user

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.
