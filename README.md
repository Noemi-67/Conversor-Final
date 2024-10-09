<h1> Bienvenido al Conversor De Moneda </h1>


Este es un proyecto en Java que permite realizar la conversión de varias monedas utilizando tasas de conversión actualizadas. El conversor toma una cantidad en una moneda de origen y la convierte a otra moneda destino, basándose en las tasas de conversión que obtiene de un servicio de API externo.

## Funcionalidades

- Convertir entre diferentes tipos de monedas: USD, ARS, BRL, COP, BOB.
- Realizar conversiones de moneda basadas en tasas de cambio actuales.
- Manejo de errores para entradas no válidas o monedas no soportadas.
- Sistema de menús para seleccionar las monedas a convertir y realizar las operaciones.

## Monedas Soportadas

El conversor de moneda actualmente soporta las siguientes conversiones:

1. USD a ARS
2. ARS a USD
3. USD a BRL
4. BRL a USD
5. USD a COP
6. COP a USD
7. USD a BOB

## Requisitos

Para ejecutar este proyecto, se requiere:

- **Java 17** o superior.
- Un entorno de desarrollo como **IntelliJ IDEA** 
- Conexión a internet (para obtener las tasas de cambio desde la API).

## Uso

1. Clona este repositorio.
2. Abre el proyecto en IntelliJ IDEA o cualquier entorno de desarrollo que prefieras.
3. Configura el SDK de Java (JDK 17 o superior).
4. Ejecuta la clase `Main` para iniciar la aplicación.

## Ejemplo de Uso

Al iniciar la aplicación, se te presentará un menú con opciones como el que te muestro. Por ejemplo, si seleccionas la opción "1", el sistema convertirá dólares estadounidenses (USD) a pesos argentinos (ARS) y asi sucesivamente.

Bienvenido/a al conversor de monedas

1) Dólar =>> Peso argentino
2) Peso argentino =>> Dólar
3) Dólar =>> Real brasileño
4) Real brasileño =>> Dólar
5) Dólar =>> Soles
6) Soles =>> Dólar
7) Dólar =>> Peso colombiano
8) Peso colombiano =>> Dólar
9) Salir
******************************************************
Elija una opción válida:
## Manejo de Errores

- Si el usuario introduce una opción no válida, el programa imprimirá un mensaje de error y pedirá una nueva entrada.
- Si la API no puede proporcionar una tasa de conversión para una moneda específica, se mostrará un mensaje de error.
- Ejemplo :si colocas 10  te dará el siguiente mensaje: Opción inválida. Por favor, elija una opción válida.


## Futuras Mejoras

- Añadir más opciones de conversión entre otras monedas.


## Contribuciones

Si deseas contribuir a este proyecto, siéntete libre de hacer un fork del repositorio y abrir un pull request con tus mejoras. Todos los comentarios y sugerencias son bienvenidos.

## Licencia

Este proyecto está licenciado bajo la [Licencia MIT](LICENSE).
