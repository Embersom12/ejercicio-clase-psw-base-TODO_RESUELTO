# Ejercicio de clase: pruebas en una tienda de libros

Proyecto base (Spring Boot 4.1.0, Java 17, Maven).

## Cómo empezar
1. Abre esta carpeta (la que contiene `pom.xml`) en IntelliJ IDEA: File -> Open.
2. Project Structure -> SDK: JDK 17. Recarga Maven.
3. Ejecuta `EjercicioClaseApplication` (triángulo verde). Debe terminar en `Started EjercicioClaseApplication`.
4. Abre http://localhost:8080/api/libros en el navegador. Debe mostrar `[]`.

La base de datos es H2 (en memoria): no necesitas instalar nada.

## Endpoints
| Verbo y ruta | Qué hace |
| --- | --- |
| GET /api/libros | Lista los libros |
| GET /api/libros/{id} | Busca un libro |
| POST /api/libros | Registra un libro |
| POST /api/clientes/registrar | Registra un cliente |
| GET /api/clientes/login?email=&password= | Inicia sesión |

El `pom.xml` ya incluye JUnit 5, Mockito, Rest Assured, Cucumber y H2.
Las carpetas de test están vacías: ahí se desarrollan las 3 preguntas.
