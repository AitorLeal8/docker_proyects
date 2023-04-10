# docker_proyects
- Proyectos con docker (Dockerfiles, Docker-compose, etc)

##  wordpress_compose
- Proyecto para poner en marcha un wordpress con una base de datos MySQL y phpmyadmin usando docker compose con guardado de archivos al apagar los contenedores.
#### Uso:
- Necesitamos tener docker y docker-compose instalado.
- Crear un directorio y meter dentro el archivo docker-compose.yml.
- Crear en ese directorio dos direcotios vacios llamados db y web, estos directorios guardaran los archivos de wordpress y la base de datos.
- Ejecutar `docker-compose up` en una terminal dentro del directorio en el que este el archivo yml.

#### Capturas:
![Screenshot from 2023-04-10 15-20-32](https://user-images.githubusercontent.com/95700435/230911090-2da2b895-f575-467b-a00c-2bbd28f43981.png)
![Screenshot from 2023-04-10 15-20-46](https://user-images.githubusercontent.com/95700435/230911092-83f765ee-bac4-4902-926b-e6511097bffa.png)
