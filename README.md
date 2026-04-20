# Proyecto DevOps - Hola Mundo con Docker

## Descripción
Este proyecto consiste en una aplicación web simple que muestra un mensaje "Hola Mundo", dockerizada y subida a Docker Hub.

## Tecnologías utilizadas
- Node.js
- Docker

## Ejecución

1. Construir la imagen:
docker build -t rosowsky/hola-mundo .

2. Ejecutar el contenedor:
docker run -p 3001:3000 rosowsky/hola-mundo

3. Abrir en navegador:
http://localhost:3001

## Docker Hub
Imagen publicada en:
rosowsky/hola-mundo