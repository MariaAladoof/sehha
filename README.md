# Sehha — Healthcare Booking & Management System

## Overview

**Sehha** is a healthcare management and booking system built with Laravel.
The system connects patients with clinics and laboratories and provides a structured environment for managing appointments, users, roles, and permissions.

The system is designed to support multiple users with different levels of access, including a secretary role with limited permissions.

## Main Features

* Clinic appointment booking and management
* Laboratory appointment booking and management
* Patient management
* Multi-user system
* Role-based access control
* Limited permissions for secretary users
* Clinic and laboratory management
* Appointment scheduling
* Medical departments and examination types
* Notifications
* Wallet and related financial operations
* Healthcare content management
* Administrative dashboard using Filament

## User Roles & Permissions

The system supports multiple users with different permissions.

### Administrator

Has broad access to system management, including users, clinics, laboratories, appointments, and other system resources.

### Secretary

Has limited access according to the permissions assigned to the role.

The secretary can perform operational tasks without having full administrative access to the system.

### Other Users

The system is designed to support additional user roles with different permissions according to the application's requirements.

## Technology Stack

* **PHP 8.2**
* **Laravel 11**
* **MySQL / MariaDB**
* **Laravel Sanctum**
* **Filament**
* **Composer**
* **Git & GitHub**

## Architecture

The project follows Laravel's standard application structure and separates responsibilities between:

* Models
* Controllers
* Form Requests
* Migrations
* Seeders
* API routes
* Web routes
* Filament Resources
* Services and application logic

## Authentication & Authorization

Authentication is implemented using Laravel authentication mechanisms and **Laravel Sanctum** for API authentication.

The system uses role-based permissions to control access to different resources and operations.

## Project Goals

The main goal of Sehha is to provide a centralized platform for managing healthcare booking operations while maintaining controlled access for different types of users.

The project also focuses on applying practical backend development concepts such as:

* RESTful APIs
* Database relationships
* Authentication
* Authorization
* CRUD operations
* Validation
* Database migrations
* Seeders
* Role and permission management
* Git version control

## Installation

Clone the repository:

```bash
git clone https://github.com/MariaAladoof/sehha.git
```

Navigate to the project:

```bash
cd sehha
```

Install PHP dependencies:

```bash
composer install
```

Create the environment file:

```bash
cp .env.example .env
```

Generate the application key:

```bash
php artisan key:generate
```

Configure the database connection in `.env`.

Run migrations:

```bash
php artisan migrate
```

If the project requires seed data:

```bash
php artisan db:seed
```

Start the development server:

```bash
php artisan serve
```

## Security

Sensitive environment variables and credentials are not included in the repository.

The `.env` file is excluded from Git through `.gitignore`.

## Development

This repository is also used as a practical Git/GitHub workflow project, including:

* Feature branches
* Commits
* Pull Requests
* Merging
* Conflict resolution
* GitHub Actions

## Author

**Maria Aladoof**

GitHub: https://github.com/MariaAladoof
