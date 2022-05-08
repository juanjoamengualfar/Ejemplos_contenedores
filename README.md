# Ejecutando-Contenedores

## En el caso del primer ejemplo:
<p> Mediante el comando ">docker pull ubuntu:18.04", descargaremos previamente una imagen, crearemos un contenedor de "ubuntu:18.04" y accederemos a una de las shells. Si no hemos descargado la imagen antes, se descargará, para ello usaremos el comando "docker run -it ubuntu:18.04 /bin/bash". Al crear un contenedor, podemos acceder a su shell.</p>  

![Captura de pantalla 2022-05-08 a las 11 50 57](https://user-images.githubusercontent.com/91874398/167291483-37cf6a28-f97e-4c4a-b8be-5b8c19d031c8.png)

## En el caso del primer ejemplo:
<p>Para crear el contenedor centOs:18.04 y listar el contenido de la carpeta /, ejecutaremos el comando "> docker run ubuntu:18.04 ls/" Cuando se crea el contenedor, se ejecuta el comando ls / y el contenedor se detiene. Y ya no podemos acceder a él.</p>

![Captura de pantalla 2022-05-08 a las 12 01 14](https://user-images.githubusercontent.com/91874398/167291588-b74fcb98-9e23-4a2b-b099-07a8c94c1bc2.png)

## En el caso del cuarto ejemplo:
<p>Para crear un contenedor de Debian 9 y mostrar el contenido de la carpeta configurada con el parámetro -w, usaremos el comando "> docker run -it -w /etc debian:9 ls". Al crear un contenedor, ejecute el comando ls desde el directorio /etc, después de lo cual se detiene el contenedor. Y ya no podemos acceder a él. Cuando creamos contenedores, hay dos comandos que nos interesan para realizar un seguimiento de lo que hay en nuestro sistema: "docker ps" para mostrar los contenedores en ejecución (estado UP) y "docker ps -a" para mostrar todos los contenedores creados que se están ejecutando (Up). estado) o detenido (estado Salido).</p>

![Captura de pantalla 2022-05-08 a las 11 57 03](https://user-images.githubusercontent.com/91874398/167291676-3765a7be-ac63-4005-88d2-01a9c6f52f5e.png)
