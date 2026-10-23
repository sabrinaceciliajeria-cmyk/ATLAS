# ATLAS

**ATLAS** es un asistente personal de inteligencia artificial diseñado para interactuar con el usuario mediante lenguaje natural, consultar información y ayudar a ejecutar tareas de forma segura.

El proyecto se desarrolla como un portfolio de ingeniería de software, priorizando la simplicidad, la seguridad, las buenas prácticas y una evolución progresiva.

## Objetivos

- Crear una interfaz conversacional.
- Integrar modelos de inteligencia artificial.
- Gestionar tareas y recordatorios.
- Consultar y gestionar eventos de Google Calendar.
- Consultar y resumir correos de Gmail.
- Mantener una arquitectura modular, testeable y mantenible.
- Incorporar voz como mejora futura.

## Stack tecnológico

### Backend

- Java 21
- Spring Boot
- Spring Data JPA
- PostgreSQL
- APIs de Google y OAuth 2.0

### Frontend

- React
- TypeScript
- pnpm

### Infraestructura y calidad

- Git y GitHub
- Docker y Docker Compose
- Pruebas unitarias y de integración
- Documentación técnica

## Arquitectura

ATLAS comenzará como un monolito modular. El backend aplicará principios de Clean Architecture y arquitectura hexagonal cuando aporten valor, separando las reglas de negocio de los detalles técnicos.

```text
Atlas/
├── backend/       # API y lógica de negocio en Java
├── frontend/      # Interfaz React + TypeScript
├── docs/
│   ├── architecture/
│   ├── decisions/
│   └── guides/
├── .env.example
├── .gitignore
└── README.md
```

## Seguridad

- No incluir credenciales ni secretos en Git.
- Utilizar variables de entorno para la configuración sensible.
- Solicitar confirmación antes de ejecutar acciones que modifiquen datos.
- Minimizar los datos personales enviados a modelos de IA.
- Utilizar datos ficticios en las demostraciones del portfolio.

## Roadmap

1. Preparar el entorno y la estructura del proyecto.
2. Crear una API inicial y una interfaz conversacional.
3. Incorporar PostgreSQL y la gestión de tareas.
4. Integrar Google Calendar mediante OAuth 2.0.
5. Integrar Gmail y el resumen de correos.
6. Incorporar IA y generar un briefing diario.
7. Añadir pruebas, controles de seguridad y manejo de errores.
8. Preparar Docker, documentación y despliegue.
9. Explorar la interacción por voz.

## Estado actual

**Fase 0 — Preparación del proyecto.**

Se está organizando el repositorio antes de iniciar la implementación del backend y el frontend.

## Principios de desarrollo

1. Simplicidad antes que complejidad.
2. Separación clara de responsabilidades.
3. Seguridad desde el diseño.
4. Código testeable y mantenible.
5. Decisiones técnicas justificadas.
6. Documentación útil y actualizada.
7. Evolución incremental con commits pequeños y descriptivos.
