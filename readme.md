## Construye un CMS desde cero con Laravel y Vue
Este es un ejemplo de cómo construir un CMS desde cero con Laravel y Vue. Puedes leer el artículo sobre Pusher aquí:

* https://pusher.com/tutorials/cms-laravel-vue-part-1 (BUILD A CMS WITH LARAVEL AND VUE - PART 1: SETTING UP)
* https://pusher.com/tutorials/cms-laravel-vue-part-2 (BUILD A CMS WITH LARAVEL AND VUE - PART 2: IMPLEMENTING POSTS)
* https://pusher.com/tutorials/cms-laravel-vue-part-3 (BUILD A CMS WITH LARAVEL AND VUE - PART 3: BUILDING AN API)
* https://pusher.com/tutorials/cms-laravel-vue-part-4 (BUILD A CMS WITH LARAVEL AND VUE - PART 4: BUILDING THE DASHBOARD)
* https://pusher.com/tutorials/cms-laravel-vue-part-5 (BUILD A CMS WITH LARAVEL AND VUE - PART 5: COMPLETING OUR DASHBOARDS)
* https://pusher.com/tutorials/cms-laravel-vue-part-6 (BUILD A CMS WITH LARAVEL AND VUE - PART 6: ADDING REALTIME COMMENTS)


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
