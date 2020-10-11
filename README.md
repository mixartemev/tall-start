## About TALL-start

It's a starting point for create TALL stack apps.
- [Tailwind CSS](https://tailwindcss.com)
- [Alpine.js](https://github.com/alpinejs/alpine)
- [Laravel](https://laravel.com)
- [Livewire](https://laravel-livewire.com)

## Installation

```bash
php composer install
cp .env.example .env
chmod -R 777 bootstrap/cache storage
# configure your .env
php artisan key:generate
php artisan storage:link
php artisan migrate:fresh --seed
npm i
npm run dev
```
