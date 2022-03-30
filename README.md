# docker-php72-sample
Al hacer clone, mover todas las carpetas menos "/public" al root del proyecto donde queremos usar docker.


En laravel recordar cambiar el compose.json y el compose.lock para forzar la version de php que queremos.

Una vez que tenemos todos los archivos podemos configurar el docker-compose.yml como queremos.

correr: docker-compose up -d

listo.
