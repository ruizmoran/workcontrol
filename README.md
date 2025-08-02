# WorkControl

Arquitectura de microservicios con Spring Boot + PostgreSQL + Docker.

## Estructura

- `microservices/` → Contiene todos los microservicios Spring Boot.
- `environment/` → Contiene Docker Compose y la base de datos PostgreSQL.
- `mavenConfig/` → Espacio reservado para configuración Maven común futura.

## Cómo empezar

```bash
cd environment
docker-compose up --build
```