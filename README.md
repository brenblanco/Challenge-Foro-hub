# Challenge-Back-End - Foro Hub API

Foro Hub es una API REST construida con **Spring Boot** que simula un sistema de foros, permitiendo a los usuarios crear, visualizar, actualizar y eliminar tópicos. Este proyecto se enfoca en aplicar las mejores prácticas del desarrollo backend en Java, incluyendo el uso de un framework robusto, validaciones, persistencia y autenticación.

# Funcionalidades

Esta API permite:

- ✅ Crear un nuevo tópico  
- ✅ Listar todos los tópicos  
- ✅ Ver detalles de un tópico específico  
- ✅ Actualizar un tópico existente  
- ✅ Eliminar un tópico  
- ✅ Autenticarse con JWT para acceder a los endpoints protegidos  

# Tecnologías utilizadas
- Java 17+
- Spring Boot
- Spring Data JPA
- Spring Security + JWT
- Hibernate Validator
- Base de datos MySql
- Maven

# Instalación y ejecución
  Clonar el repositorio:
   git clone https://github.com/brenblanco/Challenge-Foro-hub.git

# Estructura del proyecto   

# Seguridad
  Autenticación basada en tokens JWT.
  Rutas protegidas: creación, edición y eliminación requieren autenticación.
  Login con usuario y contraseña usando Spring Security.

# Ejemplos de uso (endpoints)
- ✅ Crear tópico
     POST /topicos

    {
      "titulo": "Error al compilar en Java",
      "mensaje": "Estoy recibiendo un error al usar Maven...",
      "autor": "Brenda",
      "curso": "Java Backend"
    }
  
- ✅ Listar todos los tópicos
     GET /topicos

- ✅ Ver un tópico específico
     GET /topicos/{id}

- ✅ Actualizar un tópico
     PUT /topicos/{id}

    {
      "titulo": "Error solucionado",
      "mensaje": "Era un problema con el JDK."
    }
  
- ✅ Eliminar un tópico
      DELETE /topicos/{id}

  👩‍💻 Desarrollado por
Brenda — Desarrolladora Backend Jr
Proyecto realizado como parte de desafío formativo con enfoque en APIs REST con Spring Boot.

   
  
