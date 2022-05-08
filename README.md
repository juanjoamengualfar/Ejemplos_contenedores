# Ejemplos de ejecuciones de contenedores:

## En el caso del primer ejemplo:
<p> Mediante el comando "docker pull ubuntu:18.04", descargaremos previamente una imagen, crearemos un contenedor de "ubuntu:18.04" y accederemos a una de las shells. Si no hemos descargado la imagen antes, se descargará, para ello usaremos el comando "docker run -it ubuntu:18.04 /bin/bash". Al crear un contenedor, podemos acceder a su shell.</p>  

![Captura1](https://user-images.githubusercontent.com/91874635/167316647-692b71b8-02fa-4b96-80de-acb6b10c2787.PNG)

## En el caso del primer ejemplo:
<p> Para crear el contenedor centOs:18.04 y listar el contenido de la carpeta /, ejecutaremos el comando "docker run ubuntu:18.04 ls/" Cuando se crea el contenedor, se ejecuta el comando ls / y el contenedor se detiene. Y ya no podemos acceder a él.</p>

![Captura2](https://user-images.githubusercontent.com/91874635/167316649-ccb5d310-1923-4a14-9f8e-3d81d2de158f.PNG)

## En el caso del cuarto ejemplo:
<p>Para crear un contenedor de Debian 9 y mostrar el contenido de la carpeta configurada con el parámetro -w, usaremos el comando "docker run -it -w /etc debian:9 ls". Al crear un contenedor, ejecute el comando ls desde el directorio /etc, después de lo cual se detiene el contenedor. Y ya no podemos acceder a él. Cuando creamos contenedores, hay dos comandos que nos interesan para realizar un seguimiento de lo que hay en nuestro sistema: "docker ps" para mostrar los contenedores en ejecución (estado UP) y "docker ps -a" para mostrar todos los contenedores creados que se están ejecutando (Up). estado) o detenido (estado Salido).</p>

![Captura3](https://user-images.githubusercontent.com/91874635/167316650-2458ab7f-c8e3-4f21-95a6-f03475df0796.PNG)
