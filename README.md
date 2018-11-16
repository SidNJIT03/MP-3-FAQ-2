# MP-3-FAQ-2

To run the FAQ project:

1. git clone https://github.com/SidNJIT03/MP-3-FAQ-2.git
2. CD into FAQ and run composer install
3. cp .env.example to .env
4. run: php artisan key:generate
5. setup database / with sqlite or other https://laravel.com/docs/5.7/database
6. Run: php artisan migrate
7. Run: unit tests: phpunit
8. Run: seeds php artisan migrate:refresh --seed
