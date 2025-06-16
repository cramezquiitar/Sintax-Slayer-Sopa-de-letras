# Sintax-Slayer-Sopa-de-letras

### Programacion de computadores

### Universidad Nacional de Colombia

### grupo 7

### Integrantes: 
- Cristian Amezquita
- Sebastian Vega
- Nicolas Valle

# Explicacion alternativa 
Nosotros como equipo escogimos la alternativa 1 para entenderla y desarrollarla

La alternativa es: Construir una aplicación que emule una sopa de letras utilizando Python.

Para comenzar abordando el problema planteado decidimos desglosarlo y estenderlo por partes más pequeñas para facilitar el trabajo
Comenzamos sacando palabras clave, estas fueron: 

Construir: “Hacer algo utilizando los elementos adecuados.” (RAE, definición 2ª, disponible en: https://dle.rae.es/construir)

Aplicación: “Programa preparado para una utilización específica, como el pago de nóminas, el tratamiento de textos, etc.” (RAE, definición 4ª, disponible en: https://dle.rae.es/aplicación)

Emular: “Imitar las acciones de otro procurando igualarlas e incluso excederlas.” (RAE, definición 1ª, disponible en: https://dle.rae.es/emular)

Sopa de letras: "Pasatiempo consistente en encontrar ciertas palabras dentro de un cuadro compuesto de letras aparentemente desordenadas." (RAE, definición 1ª, disponible en: https://dle.rae.es/sopa)

Python: "Python es un lenguaje de programación interpretado, orientado a objetos y de alto nivel, con semántica dinámica." (Python, disponible en https://www.python.org/doc/essays/blurb/)

![image](https://github.com/user-attachments/assets/d5afc8ca-5baf-4f2d-ba82-7c76509bb56f)

## Objetivo: 
Desarrollar una aplicación en Python que genere y permita jugar una sopa de letras de tamaño mínimo 10x10 y máximo 30x30, utilizando palabras clave relacionadas con la carrera de Ingeniería Civil, aplicando los conocimientos adquiridos durante el curso de programación.

## Objetivos especificos
-Implementar estructuras de datos adecuadas (listas, matrices) para representar el tablero de la sopa de letras y gestionar el contenido de forma dinámica.

-Aplicar algoritmos de inserción y búsqueda de palabras en distintas direcciones (horizontal, vertical y diagonal), asegurando que estas no se sobrepongan incorrectamente ni excedan los límites de la matriz.

-Automatizar el proceso de generación del tablero, incluyendo la inserción de letras aleatorias en los espacios vacíos para camuflar las palabras ocultas.

-Diseñar una interfaz simple en consola que permita al usuario interactuar con el juego, ingresar palabras, recibir retroalimentación y visualizar el tablero actualizado.

-Integrar un conjunto de palabras relacionadas con Ingeniería Civil, tales como: cimentación, hormigón, estructura, acero, plano, geotecnia, topografía, entre otras, promoviendo así la familiarización con el vocabulario técnico de la profesión.

-Fomentar la reutilización del código mediante el uso de funciones y/o módulos, favoreciendo el desarrollo estructurado, legible y mantenible.

-Incorporar elementos básicos de validación y control de errores, como verificar la validez de palabras ingresadas o el rango del tablero.

## Lluvia de ideas:

Decidimos hacer una lluvia de ideas para entender el problema y plantear cómo abordar la solución. Algunas de las ideas fueron: 

### -FUNCIONALIDADES BÁSICAS
Generar sopa de letras en consola.

Cargar lista de palabras desde archivo.

Insertar palabras en direcciones: horizontal, vertical, diagonal.

Verificar si una palabra ingresada por el usuario está en la sopa.

Mostrar la palabra encontrada resaltada (con colores o mayúsculas).

Limitar número de intentos por palabra.

### POSIBLES MECÁNICAS DE JUEGO
Dificultad seleccionable (tamaño de matriz, número de palabras).

Temporizador para resolver la sopa.

Puntuación por palabra encontrada.

Penalización por errores o tiempo.

Modo contrarreloj o por turnos.

### -ALGORITMOS Y LÓGICA
Algoritmo de inserción de palabras sin que estas se sobrepongan o obstaculiccen el juego.

Uso de matrices (listas anidadas) para representar el tablero.

Búsqueda en 8 direcciones (↔ ↕ ↘ ↙ ↗ ↖).

Marcar letras usadas para evitar sobreposiciones inválidas.

Algoritmo de validación rápida de respuestas.
