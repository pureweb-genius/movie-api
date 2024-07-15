# Laravel Movie Database

This project is a simple Laravel application for managing movies and genres. The project includes migrations, models, controllers, and APIs for working with movies and genres.

## The project includes:
- Models for interacting with genres and movies.
- Controllers for creating, updating, and deleting records.
- REST APIs for managing data on genres and movies.
## Installation

### 1. Clone the repository

```bash
  git clone https://github.com/pureweb-genius/movie-api.git

```
### 2. Install dependencies
```bash
composer install
```
### 3. Copy and update environment file
```bash
cp .env.example .env
```
```bash
php artisan key:generate
```

### 4. Start Docker containers
```bash
./vendor/bin/sail up -d
./vendor/bin/sail artisan migrate --seed
```
