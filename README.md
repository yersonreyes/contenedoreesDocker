# Contenedores Docker

Este repositorio contiene configuraciones para ejecutar `docker compose` de distintos servicios. La idea es centralizar los stacks que uso para desarrollo y pruebas, manteniendo cada servicio en su propia carpeta.

## Estructura
- Cada directorio posee su archivo `dockercompose.yml` y cualquier configuracion auxiliar necesaria para el servicio.
- Algunos ejemplos son Portainer, un proxy nginx y otros servicios complementarios.

## Como usarlo
1. Ingresa al directorio del servicio que desees levantar.
2. Ajusta las variables de entorno o volumenes segun tus necesidades.
3. Ejecuta `docker compose up -d` (o `docker-compose` segun tu version) para iniciar los contenedores.
