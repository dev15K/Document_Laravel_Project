# README.md

## Table of Contents

* [php](https://www.php.net/)
* [composer](https://getcomposer.org/)
* [laravel](https://laravel.com/)

## How to install php

### If you are using macOS

An easy way to install PHP on macOS is with the [Homebrew](https://brew.sh/) packaging manager.

1. Install Homebrew by following the instructions on the website.
2. Run the following command to install PHP:

```bash
brew install php
```

### If you are using Linux

```bash
sudo apt-get install php
```

### If you are using Windows

You can download and install the latest version of PHP from the [official website](https://www.php.net/downloads.php).

After downloading the installer, run it to install PHP.

Or you can download [xampp](https://www.apachefriends.org/index.html) and install PHP from there.
If can't download [xampp](https://download.com.vn/)(8.2.12), please
visit [LINK](https://download.com.vn/xampp-for-windows-14235)(8.2.12) to download.

#### ACTIVE PHP ON WINDOWS

1. After download xampp, please open xampp control panel.
2. On the start button, search for: Environment Variables.
3. Click on the Edit button.
4. Click on the Environment Variables button.
5. In the System Variables section, select the Path variable and click on the Edit button.
6. Click on the New button and type %xampp%\php\php.exe (such as: C:\xampp\php\php.exe).
7. Click on the OK button.

## How to use php

```bash
php -v
```

## How to install composer

### If you are using macOS

An easy way to install composer on macOS is with the [Homebrew](https://brew.sh/) packaging manager.

1. Install Homebrew by following the instructions on the website.
2. Run the following command to install composer:

```bash
brew install composer
```

### If you are using Linux

```bash
sudo apt-get install composer
```

### If you are using Windows

You can download and install the latest version of composer from
the [official website](https://getcomposer.org/download/).

After downloading the installer, run it to install composer.

Or you can download [composer](https://getcomposer.org/) and install composer from there.

## How to use composer

```bash
composer -v
```

## How to install laravel

```bash
composer create-project --prefer-dist laravel/laravel
```

If you want to create project laravel with version 10.0.0, you can use this command:

```bash
composer create-project --prefer-dist laravel/laravel:^10.0
```

see more to other versions of laravel, such as 8.0, 9.0, etc.

## How to use laravel

### Create new environment

```bash
cp .env.example .env

### if windows

copy .env.example .env
```

After create .env, you can see the .env file in the root of your project.
And update the database credentials in .env file.

### Update database credentials in .env file

```bash
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=laravel
DB_USERNAME=root
DB_PASSWORD=
```

### Install dependencies

```bash
composer install
```

if you want to update dependencies, you can use this command:

```bash
composer update
```

### Run migrations

```bash
php artisan migrate
```

### Run seeders

```bash
php artisan db:seed
```

### Run all database

```bash
php artisan migrate:fresh --seed
```

### Generate key

```bash
php artisan key:generate
```

### Run server

```bash
php artisan serve
```

## How to use phpunit

```bash
php artisan test
```

## How to use php artisan

```bash
php artisan
```

And see more command [here](https://laravel.com/docs/10.x/artisan).

## More command others

```bash
composer dump-autoload ## dump autoload

php artisan make: 
### option ###
- controller
- model
- migration
- seeder
- factory
- request
- resource
- event
- job
- listener
- notification
- policy
- provider
- rule
- test
- console
- facade
- middleware

php artisan optimize:clear ## optimize clear
```
## Try Laravel
### [Laravel Project](https://github.com/dev15K/LaravelCart)