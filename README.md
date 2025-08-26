# fincaSmart
Este proyecto es una aplicación para la gestión de reservas de fincas para eventos y turismo rural.
Tecnologías usadas:

Backend:
- Spring web
- Spring Data JPA + PostgreSQL
- Spring Security + JWT
- Lombok
- Swagger/OpenAPI
Frontend:
- Angular CLI
- FullCalendar
- HttpClient para consumo de la API

Funcionalidades Principales:
- Registro y autenticación de usuarios (Admin, Dueños, Clientes).
- Gestión de fincas (CRUD: crear, editar, eliminar, listar).
- Calendario de disponibilidad y control de estados (disponible, ocupado, mantenimiento).
- Calendario de disponibilidad y control de estados (disponible, ocupado, mantenimiento).
- Notificaciones por correo al confirmar reserva.
- Panel de administración con estadísticas básicas.

Estructura del repositorio:
/backend-springboot   → API REST en Spring Boot
/frontend-angular     → Aplicación web en Angular
/mobile-flutter       → Aplicación móvil en Flutter

Reglas de Colaboración:
- Rama principal: main
- Rama de desarrollo: develop
- Ramas de características: feature/*
- Ramas de correcciones: hotfix/*
Buenas Practicas:
- Todo cambio debe hacerse desde una rama feature/*.
- Antes de hacer merge, se debe crear un Pull Request y esperar almenos 1 aprobación.
- El código debe pasar por revision usando el checklist del proyecto.
- La rama main debe estár protegida contra pushes directos.
