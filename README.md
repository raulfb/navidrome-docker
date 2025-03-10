# Navidrome con Docker Compose

Configuración para ejecutar Navidrome utilizando Docker Compose.

## Requisitos

- Docker
- Docker Compose

## Crear carpetas data y music
Crearr las carrpetas data y music necesarias para que navidrome funcione:

```
mkdir data music
```
## Agrega música
Colocar archivos de música en la carpeta music

## Arrancar servicio
```
docker compose up -d
```
## URL Acceso
```
http://<IP-de-tu-servidor>:3002
```