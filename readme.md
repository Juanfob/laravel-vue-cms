## Construye un CMS desde cero con Laravel y Vue
Este es un ejemplo de cómo construir un CMS desde cero con Laravel y Vue. Puedes leer el artículo sobre Pusher aquí:

https://pusher.com/tutorials/cms-laravel-vue-part-1

* Descargar o clonar el proyecto.
* CD al directorio del proyecto.
* Renombrar .env.ejemplo a .env
* Ejecute el comando composer install.
* Ejecute el comando php artesano clave: generar para generar una clave de aplicación.
*Configure los ajustes de la base de datos en el archivo .env.
* Actualice las claves PUSHER_APP_ * en el archivo .env.
* Cambie el BROADCAST_DRIVER a empujer.
* Migre la base de datos ejecutando este comando: php artisan migrate --seed.
* Ejecute el comando: php artisan serve para iniciar la aplicación.

Laravel 5.8.26
