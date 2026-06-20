# Instalación

!!! warning
Asegúrate de tener Docker y Docker Compose instalados antes de comenzar.

## Requisitos

* Docker
* Docker Compose
* Git
* Node.js 22+
* Java 21 (si se utiliza backend Spring Boot)

## Clonar el repositorio

```bash
git clone https://github.com/jacobo0991/nextcut.git
cd nextcut
```

## Iniciar los servicios

```bash
docker compose up -d
```

## Verificar el sistema

Frontend:

```text
http://localhost:3000
```

Backend:

```text
http://localhost:8080
```

## Estructura del proyecto

```text
frontend/
backend/
database/
docker-compose.yml
```

Ir a la sección de [Casos de Uso](uso.md).
