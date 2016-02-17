# Backup-PHP-MySQL

Todas las base de datos deben ser respladadas y muchas veces se hace en forma manual, pero existe una forma muy sencilla utilizando PHP de hacer el respaldo de su base de datos y manener su sistema un poco más seguro.


Con este script usted puede pasar una tabla específica para copia de seguridad u optar por toda la base de datos.

## Cómo implementar

La mejor manera de utilizar el script es usuar el CRON de su Hosting para crear una tarea programada la cual se ejecutará automaticamente cada vez segun la configuración.


## El uso de CRON

wget -O / dev / null http://your-site.com/database_backup/backup.php

## Futuras Implementaciones

 - Comprimir el sql resultante
 - Enviarlo a un correo electrónico o subirlo a un dropbox configurado
 - hacer no solo el backup de la base de datos si no tambien algunas carpetas determinadas
