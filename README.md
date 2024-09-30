# install guide

clone project from github

```
git clone https://github.com/oneziro/oneziro-shop.git 
cd oneziro-shop
```

install laravel and project dependencies
```
composer install
```
create environment file and create laravel private key
```
cp .env.example .env && php artisan key:generate 
```

install application migration
```
php artisan migrate
```

run laravel application
```
php artisan serve
```


# dependencies

-----

- Filament/filament



## toDo
-[ ] add admin user filter for filament
