# Laravel Task Management System

A simple Laravel-based task management system to showcase your skills on GitHub and Upwork.

## Features

- User Authentication (Admin/User roles)
- Create, Update, Delete, and Assign Tasks
- Task due dates, status updates, and notifications
- Dashboard with summary widgets
- Bootstrap UI

## Tech Stack

- Laravel 10.x
- MySQL / SQLite
- Bootstrap 5
- Laravel Breeze (for auth)

## Setup Instructions

```bash
git clone https://github.com/yourusername/laravel-task-manager.git
cd laravel-task-manager
composer install
cp .env.example .env
php artisan key:generate
php artisan migrate
php artisan serve
```

## License

MIT