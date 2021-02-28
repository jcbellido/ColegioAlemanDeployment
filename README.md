# Detalles del despliegue

Este repositorio contiene una definición del despliegue de servicios para la Escuela Alemana utilizando un fichero `docker-compose`.

En un equipo con [Docker](https://www.docker.com/) instalado, ejecutar:

```
docker-compose.exe up 
````
desde éste directorio debería levantar 4 servicios.

1. PostgreSQL
1. PGAdmin como herramienta para la DB
1. Backend + API
1. Servidor Web

Nota: En este momento del desarrollo estamos aún trabajando en los servicios y los puertos y accesos pueden cambiar.

## Accediendo a la web del departamento

Tras levantar docker-compose la web debería estar accesible con una conexión a [Localhost:1337](http://localhost:1337)

