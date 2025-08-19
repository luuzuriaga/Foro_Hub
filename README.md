# Foro_Hub 💬

API REST construida con **Java + Spring Boot** para gestionar tópicos de discusión.  
Permite crear, listar, actualizar y eliminar tópicos, además de manejar usuarios, respuestas y autenticación con JWT.

---

## 🚀 Tecnologías
- Java 17
- Spring Boot
- Maven
- MySQL / MariaDB
- JPA + Spring Data
- Flyway (migraciones)
- Spring Security + JWT
- OpenAPI (documentación)

---

## 📁 Estructura
- **application** → DTOs y servicios
- **domain** → entidades y repositorios
- **infrastructure** → configuración, seguridad y excepciones
- **presentation** → controladores REST

---

## ✅ Funcionalidades
- CRUD de tópicos con paginación y búsqueda.
- Gestión de usuarios, perfiles y respuestas.
- Manejo global de excepciones.
- Autenticación y autorización con JWT.
- Envío de correos en registro de usuarios.

---

## 🖥️ Ejecución
1. Requisitos: **Java 17**, **Maven**, **MySQL/MariaDB**.
2. Configura la BD y el secreto JWT en `application.properties`.
3. Ejecuta el proyecto:
   ```bash
   ./mvnw spring-boot:run
ll