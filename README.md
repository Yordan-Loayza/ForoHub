# ForoHub

ForoHub es una plataforma educativa basada en Spring Boot, 
donde usuarios pueden crear, gestionar y participar en foros relacionados con cursos
y temas educativos.

---
### Pasos
1. Clona el repositorio:
   ```bash
   git clone https://github.com/Yordan-Loayza/ForoHub.git
   cd ForoHub
   ```
2. Configura tu base de datos MySQL en application.properties:
   ```bash
   spring.datasource.url=jdbc:mysql://localhost:3306/forohub
   spring.datasource.username=tu_usuario
   spring.datasource.password=tu_contraseña
   ```
3. A correr el programa:
   ```bash
   mvn clean install
   mvn spring-boot:run
   ```
   
## **API Endpoints**

| Método | Endpoint               | Descripción                          |
|--------|------------------------|--------------------------------------|
| POST   | `/auth/login`           | Iniciar sesión.                     |
| GET    | `/users`                | Obtener lista de usuarios.          |
| GET    | `/topics`               | Ver temas.                           |
| POST   | `/topics`               | Crear un tema.                       |
| GET    | `/courses`              | Listar cursos.                      |
| POST   | `/responses`            | Publicar respuesta.                 |
