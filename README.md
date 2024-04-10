# dvwa-docker-compose

Este repositorio contiene un archivo `docker-compose.yml` para desplegar la aplicación [Damn Vulnerable Web Application (DVWA)][1].

[DVWA][1] es una aplicación web desarrollada en PHP y MySQL que ha sido diseñada con algunas de las vulnerabilidad más comunes que pueden aparecer en las aplicaciones web.

Puede encontrar más información en el [repositorio oficial del proyecto DVWA][1].

## Cómo desplegar la aplicación

Para desplegar la aplicación ejecute el comando:

```
docker compose up -d
```

Para detener los contenedores:

```
docker compose down
```

Para detener los contenedores y eliminar el volumen de la base de datos:

```
docker compose down -v
```

## Credenciales por defecto

Las credenciales por defecto para acceder a la aplicación son:

- username: `admin`
- password: `password`

## Referencias

- [https://github.com/digininja/DVWA][1]

[1]: https://github.com/digininja/DVWA