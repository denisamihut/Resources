# Laravel 

# Creating new project
- composer global require laravel/installer
- laravel new name

# Cloning new project
- git clone <project-name>

# Development

## Project commands

### Installing Composer
- composer install
- cp .env.example .env
- create db in phpMyAdmin and replace DB_DATABASE in .env file
- php artisan key:generate
- php artisan migrate
- php artisan serve
- access website at localhost:8000

### DB Migrations
- php artisan serve
- php artisan make:migration create_name_table
- php artisan migrate
- php artisan migrate:rollback

### Installing Breeze
- composer require laravel/breeze
- php artisan breeze:install
- npm install && npm run dev

php artisan make:model Category -m

### DB Seeding
- php artisan db:seed
- php artisan make:seeder AdminSeeder   
- php artisan make:migration add_is_admin_to_users_table

- PHP 8.1.10
- Laravel 9