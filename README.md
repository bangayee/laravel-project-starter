# Laravel Starter Project

A starter project using Laravel with integration of popular plugins such as Laravel Breeze, Spatie, and Datatable.

## Features
- **Laravel Breeze**: Simple and lightweight authentication for Laravel.
- **Spatie**: Permission management and additional features.
- **Datatable**: Interactive table display with search and filter features.

## Installation

Follow these steps to install and run this project:

1. **Clone Repository**
   ```sh
   git clone https://github.com/bangayee/laravel-project-starter.git
   cd laravel-project-starter
   ```

2. **Install Dependencies**
   ```sh
   composer install
   npm install
   npm run build
   ```

3. **Copy Configuration File**
   ```sh
   cp .env.example .env
   ```
   modify it according to your environment

4. **Generate Application Key**
   ```sh
   php artisan key:generate
   ```

5. **Link Storage**
   ```sh
   php artisan storage:link
   ```
6. **Migrate Database**
   ```sh
   php artisan migrate
   ```

7. **Seed Database**
   ```sh
   php artisan db:seed --class=RolePermissionSeeder
   php artisan db:seed --class=UserSeeder
   php artisan db:seed --class=DatabaseSeeder
   ```

8. **Start the Server**
   ```sh
   php artisan serve
   ```

## Testing Credentials
For testing purposes, use the following login information:
```
Username: admin@gmail.com
Password: 12345678
```

---
If you have any questions or issues, please create an issue in this repository or contact the project owner.

