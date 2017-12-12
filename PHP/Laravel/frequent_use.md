
```php
php artisan make:migration create_users_table
php artisan migrate
php artisan migrate:rollback
php artisan migrate:reset
php artisan migrate:refresh

php artisan make:model User

php artisan make:factory PostFactory --model=Post

php artisan db:seed
php artisan db:seed --class=UsersTableSeeder
php artisan migrate:refresh --seed
```