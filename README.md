## Описание
Тестовый проект на Laravel 8.
Реализована возможность управления правами пользователей и их привелегиями.

## Установка и запуск проекта

- Установить git-клиент
	- https://git-scm.com/download/win

- Запустить `cmd.exe`
	- Нажать **Win+R**
	- Ввести `cmd`
	- Нажать `Enter`
- Клонировать проект в окне `cmd`
	- Ввести команду `git clone https://`
- Перейти в каталог с проектом `laravel-userapp`
- Выполнить
	- composer install
	- npm install
- Внести настроики для подключения к базе данных (mysql) в файле `.env`
- В консоле запустить миграции и сиды (seeds)
	- php artisan migrate
	- php artisan db:seed
- Запустить сервер коммандои из консоли
	- php artisan serve
- В браузере перейти по адресу [http://localhost:8000](http://localhost:8000)
