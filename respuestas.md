Quiz 1 - Estructura de Datos

1. DIFERENCIA ENTRE UN IDE Y UN EDITOR DE TEXTO

*IDE (Entorno de Desarrollo Integrado):
  - Herramienta completa para desarrollo de software.
  - Incluye editor de código, depurador, compilador, y herramientas de automatización.
  - Ejemplos: IntelliJ IDEA, Eclipse, Visual Studio.

*Editor de texto:
  - Programa para escribir y editar código plano.
  - No tiene herramientas integradas para compilar o depurar.
  - Ejemplos: Visual Studio Code, Sublime Text, Atom.


 2. TIPOS DE LENGUAJES DE PROGRAMACION (TÍPADOS Y NO TÍPADOS)

*Lenguajes tipados:
  - Requieren declarar el tipo de dato de una variable.
  - Subcategorías:
    +Estáticamente tipados: Verificación de tipos en tiempo de compilación (Java, C++).
    +Dinámicamente tipados: Verificación en tiempo de ejecución (Python, JavaScript).

  *Lenguajes no tipados:
  +No requieren declarar tipos de datos (ej: lenguajes de bajo nivel como Assembly).

3.TIPOS DE DATOS EN JAVA

*Numericos..
*Enteros:
  - `byte` (8 bits), `short` (16 bits), `int` (32 bits), `long` (64 bits).
*Decimales:
  - `float` (32 bits), `double` (64 bits).

Ejemplo:
int edad = 34;
double precio = 15,88;

*Cadenas..
''Clase String para texto.
´´Inmutable (no se modifica después de su creación).
Ejemplo:
**String nombre = "Juan Pérez";

*Fechas..
Usa clases de java.time (Java 8+):

*LocalDate: Fecha (año, mes, día).
*LocalTime: Hora.
*LocalDateTime: Fecha y hora.

Ejemplo:
LocalDate hoy = LocalDate.now();
LocalDateTime ahora = LocalDateTime.now();



