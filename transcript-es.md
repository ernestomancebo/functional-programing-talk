# Programación Funcional
Es un paradigma de programación donde busca solucionar problemas a través de una función matemática.
Este paradigma de programación es del tipo declarativo, donde se enfoca en _qué resolver_, a diferencia de el tipo imperativo donde la manera de pensar es enfocada en _cómo resolverlo_.

## Principios de la Programación Funcional
### Funciones Puras (_Pure Functions_)
Las funciones no depende de alguna propiedad externa a ella, así como no modifica nada fuera de la misma; por lo que, para un valor de entrada siempre producirá la misma salida.

### Funciones de Alto Orden (_Funtions are First-Class and High-Order Functions_)
Las funciones pueden ser pasadas por parámetros a otras funciones, a la vez de que pueden ser el valor retornado por otras funciones.

### Inmutablilidad (_Immutability_)
Partiendo del principio de _Funciones Puras_, las funciones no alteran ningún dato fuera del alcance de la misma a la vez de que debe de retornar un nuevo resultado.

### Sin iteraciones (_Don't Iterate_)
Los controles de flujo y bucles no son utilizados fuera de las funciones, se utilizan las operaciones ya definidas por las funciones.

## Lenguajes de Programación Funcional
1. Elm
1. Haskell
1. Clojure
1. Elixir
1. Scala
1. Python
1. JavaScript
1. Kotlin
1. F#
1. Erglang

## Ventajas y Desventajas
### Ventajas
1. Código más predecible, pues sólo manipula de la data dentro de la función.
1. Código más legible y entendible, partiendo de que cada función describe la operación a realizare y que los datos de entrada o salida están ya definidos.
1. Código más testeable ya que no altera los datos fuera de la misma función y que siempre produce datos de salida.
1. Capacidad de implementar concurrencia y/o paralelismo al tratar la data de manera aislada.
1. Posibilidad de adoptar evaluación lenta (_lazy_), pues puede evaluar el valor de entrada y generar una salida almacenada.

### Desventajas
1. En ciertos casos, aplicar funciones puras puede reducir la legibilidad del código.
1. Utilizar recursividad en vez de bucles puede ser intimidante.
1. Combinar funciones puras con operaciones de entrada/salida puede llegar a ser una tarea compleja.
1. Inmutabilidad y recursión puede decrementar la eficacia del programa.

## Aplicaciones

## ¿Quién utiliza Programación Funcional?
---
### Fuentes
[GeekForGeeks](https://www.geeksforgeeks.org/functional-programming-paradigm/)

[Learning Functional Programming with JavaScript - Anjana Vakil](https://www.youtube.com/watch?v=e-5obm1G_FY)

[Best Languages for Functional Programming](https://www.slant.co/topics/485/~best-languages-for-learning-functional-programming)