# 🧠 Foro Hub Challenge - Back End

API REST desarrollada en Java + Spring Boot como parte del Challenge Back End de Alura Latam.
El proyecto implementa un foro educativo donde los usuarios pueden gestionar tópicos y respuestas, con un sistema de autenticación seguro mediante JWT y una arquitectura modular escalable.

## 📌 Actualmente soporta el rol ROLE_USER.

# 🚀 Características principales

## CRUD de Tópicos

- POST /topicos → Crear un nuevo tópico

- GET /topicos → Listar tópicos con paginación y ordenamiento

- GET /topicos/{id} → Consultar un tópico específico

- PUT /topicos/{id} → Editar un tópico existente

- DELETE /topicos/{id} → Eliminar un tópico

## CRUD de Usuarios y Respuestas

- Gestión completa de usuarios (/usuarios)

- Creación y visualización de respuestas (/respuestas)

- Autenticación & Seguridad

- Inicio de sesión con JWT

- Protección de rutas con filtros de seguridad

- Acceso restringido según rol (ROLE_USER)

- Exploración de API con Swagger

- Documentación interactiva de todos los endpoints

- Descripciones de parámetros y respuestas

## 🧪 Validaciones y reglas de negocio

- Validación de campos obligatorios en solicitudes
- Asociación automática de tópicos y respuestas al usuario autenticado
- Control de acceso mediante anotaciones y filtros de seguridad

## 📂 Estructura del proyecto

src/
 ├── controller/   → Controladores REST (endpoints)
 ├── domain/       → Entidades y lógica de negocio
 ├── infra/        → Configuración, seguridad y excepciones
 └── repository/   → Interfaces de persistencia con JPA

## 🔧 Tecnologías utilizadas

Lenguaje & Frameworks → Java 21 · Spring Boot 3 · Spring Security

Autenticación → JWT

Persistencia → JPA + Hibernate · PostgreSQL

Testing → JUnit 5 · Mockito

Documentación → Swagger / OpenAPI

Gestión de dependencias → Maven

## 🧪 Testing

Pruebas unitarias con JUnit 5 + Mockito

Validación de controladores, servicios y reglas de negocio


## 👤 Autor

Nombre: Jesus Gil Vargas

<a href="https://github.com/datamasterdev" target="_blank">GitHub: datamaster </a>
