# docker-laravel-alpine

Dockerfile para desarrollar aplicaciones Laravel con soporte para Redis

Comandos para construir la imagen y correr el entorno de desarrollo en Docker
- docker build -t laravelalpine:latest -f Dockerfile.alpine .
- docker run -p 8000:8000 --name laravelalpine laravelalpine:latest
