## Descripción del Proyecto

Es un proyecto desarrollado en Java y Spring Boot diseñada para la gestión de libros y autores. Permite buscar y gestionar información de libros y autores, integrándose con la API pública de **Gutendex** para enriquecer los datos almacenados en una base de datos local. Este proyecto es ideal para aprender sobre desarrollo backend, manejo de bases de datos y consumo de APIs.

---
## Funcionalidades

1. **Buscar libros por título:**  
   Permite buscar libros almacenados en la base de datos o realizar consultas a la API de Gutendex en caso de no encontrarlos.

2. **Buscar autor por nombre y/o apellido:**  
   Permite buscar autores por coincidencia parcial de nombre o apellido.

3. **Mostrar todos los libros:**  
   Lista todos los libros disponibles en la base de datos.

4. **Mostrar todos los autores:**  
   Lista todos los autores disponibles en la base de datos.

5. **Listar libros por idioma:**  
   Permite listar libros según el idioma especificado por el usuario.

6. **Listar autores vivos en un año específico:**  
   Lista los autores que estaban vivos en un año determinado, considerando sus fechas de nacimiento y fallecimiento.

7. **Eliminar libros:**  
   Elimina libros de la base de datos solicitando confirmación al usuario.

8. **Persistencia de datos:**  
   Los datos consultados se guardan automáticamente en una base de datos PostgreSQL para futuros accesos rápidos.

9. **Validación de datos:**  
   La aplicación realiza validaciones para asegurar la consistencia de los datos ingresados y mostrados al usuario.

---
## Tecnologías Utilizadas

- **Lenguaje de Programación:** Java 17
- **Framework:** Spring Boot 3.4.1
- **Base de Datos:** PostgreSQL
- **Consumo de API:** RestTemplate (Gutendex API)
- **Serialización y Deserialización de JSON:** Jackson
- **Validación:** Hibernate Validator
- **Gestión de Dependencias:** Maven
- **IDE Recomendado:** IntelliJ IDEA / Visual Studio Code
- **Integración y Construcción:** Spring Data JPA

---
