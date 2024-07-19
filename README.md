
# Kotlin: Introducción y Conceptos Básicos

 ## Definiciones de Variables

 En Kotlin, las variables se definen utilizando val y var:

- val: Para variables inmutables (constantes).
- var: Para variables mutables.
Ejemplos:

val pi = 3.14  // Variable inmutable

var contador = 0  // Variable mutable

## Manejo de Nulos
Kotlin maneja valores nulos de manera segura con el sistema de tipos. Para permitir valores nulos, se utiliza el operador ? después del tipo de dato.

Ejemplo:

var nombre: String? = null  // Variable que puede ser nula

Se utilizan operadores como ?., ?:, !!. y funciones como let, run para trabajar con valores nulos de manera segura.

## Tipos Opcionales

Kotlin no tiene tipos opcionales explícitos. El manejo de nulos y tipos de datos nullable sirve para propósitos similares.

## Comentarios
Kotlin utiliza:

// para comentarios de una línea.

/* */ para comentarios de múltiples líneas.

Ejemplo:

// Comentario de una línea

/*
   Comentario
   de múltiples líneas
*/

Los comentarios son útiles para explicar el código y hacerlo más legible.




