
<h1 align="center">Burrero Service Epsilon ɛ</h1>

<p align="center">
  Epsilon. The BurreroCore Base App.
</p>

## Usage

```php
sail up
sail up -d //detach mode
sail down
```
## Initial Configuration

```php
// config/app.php
use Illuminate\Support\Facades\Facade;
use Illuminate\Support\ServiceProvider;

return [
    ...
    'timezone' => 'America/Caracas',
    ...
```
## Run Vite Dev & Production Build

```php
sail npm run dev
sail npm run build
```
## May be necessary

```js
//vite.config.js
export default defineConfig({
    server: {
        hmr: {
            host: 'localhost',
        },
    },
    ...
```

## When necessary

```php
sail artisan config:clear
sail artisan cache:clear
```
## Introduction

Sail provides a Docker powered local development experience for Laravel that is compatible with macOS, Windows (WSL2), and Linux. Other than Docker, no software or libraries are required to be installed on your local computer before using Sail. Sail's simple CLI means you can start building your Laravel application without any previous Docker experience.

## Official Documentation

Documentation for Sail can be found on the [Laravel website](https://laravel.com/docs/sail).

## Security Vulnerabilities

If you discover a security vulnerability within Laravel, please send an e-mail to Carlos Guillen via [dev@burrerosoft.com](mailto:dev@burrerosoft.com). All security vulnerabilities will be promptly addressed.