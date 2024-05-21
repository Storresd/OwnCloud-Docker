Modificar el puerto, ruta donde guardar los archivos, usuario y contraseña por los deseados.
</br>
En caso de necesitar escanear archivos movidos desde terminal, OwnCloud no realiza escaneos, para ello tendremos que realizar lo siguiente:</br>
-docker exec -it owncloud /bin/bash </br>
-apt update & apt install sudo </br>
-sudo -u www-data php occ files:scan --all </br>
</br>
Listo, ya podemos salir del contenedor con exit.
