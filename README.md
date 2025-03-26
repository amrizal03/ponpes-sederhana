1. edit .env configuration and make database name like: ponpes or uptoyou
2. run migration: php artisan migrate
3. run seeder: php artisan db:seed
4. generate APP_KEY: php artisan key:generate
5. clear cache config: php artisan config:cache
6. and then run: php artisan serve

if you want to login, look at file "UserSeeder.php"
