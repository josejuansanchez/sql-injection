# dvwa-docker-compose

Este repositorio contiene un archivo `docker-compose.yml` para desplegar la aplicación [Damn Vulnerable Web Application (DVWA)][1].

DVWA es una aplicación web desarrollada en PHP y MySQL que ha sido diseñada con algunas de las vulnerabilidad más comunes que pueden aparecer en las aplicaciones web.

El repositorio oficial del proyecto DVWA está disponible en:

- [https://github.com/digininja/DVWA][1]

## Pasos para desplegar el proyecto

Creamos los contenedores con `docker compose`:

```
docker compose up -d
```

Para detener los contenedores:

```
docker compose down
```

Si queremos eliminar los contenedores y los volúmenes:

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