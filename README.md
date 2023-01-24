# My Music API

## Setup

Clone the project

```
git clone https://github.com/Akmdvtm/my-music-api.git
```

Then
```
composer install 

cp .env.example .env 

php artisan cache:clear 

composer dump-autoload 

php artisan key:generate

php artisan serve
```

Create a DATABASE an then run the command 
```
php artisan migrate
```
