# Laravel 11 - Livewire

Membuat Data Mahasiswa Sederhana Dengan Livewire

## Installation

```bash
  git clone https://github.com/hndko/laravel_livewire3.git
  composer Install
  php artisan key:generate
  cp .env.example .env
```

## Documentation

Change .env database

```bash
APP_TIMEZONE=UTC

APP_LOCALE=en
APP_FALLBACK_LOCALE=en
APP_FAKER_LOCALE=en_US

DB_CONNECTION=sqlite
# DB_HOST=127.0.0.1
# DB_PORT=3306
# DB_DATABASE=laravel
# DB_USERNAME=root
# DB_PASSWORD=
```

To

```bash
APP_TIMEZONE=Asia/Jakarta

APP_LOCALE=id
APP_FALLBACK_LOCALE=id
APP_FAKER_LOCALE=id_ID

DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=laravel_livewire3
DB_USERNAME=root
DB_PASSWORD=
```

And Then

```bash
php artisan migrate
php artisan serve
```

## Support

For support, email hd.doko22@gmail.com or join our KodeKreatif channel.
