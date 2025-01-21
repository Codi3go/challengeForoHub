# challengeForoHub

## Descripción

Este proyecto es una API REST enfocada en la gestión de tópicos dentro de un foro. Proporciona a los usuarios la capacidad de:

- Crear un nuevo tópico.
- Mostrar todos los tópicos creados.
- Mostrar un tópico específico.
- Actualizar un tópico.
- Eliminar un tópico.

### Objetivos del Proyecto

Los objetivos principales de este reto son:

1. Implementar una API REST siguiendo las mejores prácticas del modelo REST.
2. Realizar validaciones según las reglas de negocio.
3. Implementar una base de datos relacional para la persistencia de información.
4. Incorporar un servicio de autenticación y autorización mediante JWT.
5. Documentar la API utilizando Swagger.

### Funcionalidades Extra

El proyecto también incluye rutas adicionales para:

- **/usuario**: Gestión de usuarios.
- **/respuestas**: Manejo de respuestas dentro de los tópicos.

---

## Tecnologías y Herramientas

### Versiones Utilizadas

- **Java**: versión 17
- **Maven**: versión 4 o superior
- **Spring Boot**: versión 3.2.3
- **MySQL**: versión 8 o superior
- **PostgreSQL**: versión 16 o superior

### Dependencias

- Lombok
- Spring Web
- Spring Boot DevTools
- Spring Data JPA
- Flyway Migration
- MySQL Driver
- Validation
- Spring Security
- Spring Doc
- Auth0 (Java JWT)

---

## Documentación

Toda la documentación del proyecto fue realizada con la librería **SpringDoc**. Para acceder a ella en una interfaz amigable, utiliza la siguiente ruta en tu navegador:

```
{ruta_de_la_API}/swagger-ui/index.html#/
```

---

## Configuración del Entorno

1. **Clonar el repositorio:**
   ```bash
   git clone https://github.com/Codi3go/challengeForoHub.git
   ```
2. **Configurar la base de datos:**
   - Asegúrate de tener instalada y configurada una instancia de MySQL o PostgreSQL.
   - Actualiza el archivo `application.properties` o `application.yml` con las credenciales de tu base de datos.
3. **Ejecutar migraciones:**
   - Usa Flyway para aplicar las migraciones de la base de datos.
4. **Ejecutar la aplicación:**
   ```bash
   mvn spring-boot:run
   ```

---

## Licencia

Este proyecto está licenciado bajo la licencia MIT. Consulta el archivo `LICENSE` para más detalles.

---

## Contribuciones

Si deseas contribuir a este proyecto:

1. Realiza un fork del repositorio.
2. Crea una rama para tu función o corrección:
   ```bash
   git checkout -b feature/nueva-funcionalidad
   ```
3. Realiza tus cambios y haz un commit:
   ```bash
   git commit -m "Agrega nueva funcionalidad"
   ```
4. Envía un pull request explicando tus cambios.

---


