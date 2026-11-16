# School Management (Laravel)

## Installation
1. composer install
2. Copy `.env.example` to `.env`
3. php artisan key:generate
4. Create a MySQL database (e.g. `managestudent`) and set DB_DATABASE in `.env`
5. php artisan migrate
6. php artisan serve

Open http://127.0.0.1:8000/students