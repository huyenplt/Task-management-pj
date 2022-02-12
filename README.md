# Task Management

## Installation

#### Cloning the repo

1. Open a Terminal in your projects directory 
2. Clone this repo

```shell
$ git clone https://github.com/huyenplt/Task-management-pj.git

```
### Setup
```bash
# Install NPM dependencies
npm install 
# or If you like yarn
yarn

```

```bash
# Remember place your laravel-app info there:
cp .env.example .env

```

Setup
```bash
# composer install
composer install
# generate key
php artisan key:generate
# run migrations
php artisan migrate
# run frontend
npm run dev
# run backend
php artisan serve
```

## To storage image
```bash
# add this line to .env file
FILESYSTEM_DRIVER=public
php artisan storage:link

