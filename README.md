# To do 09:

1 - ¿Qué es una coroutine en Kotlin y cómo se diferencia de un hilo tradicional?

* Las coroutines son más ligeras y más eficientes en el uso de recursos; las coroutines son concurrencia
cooperativa, lo que significa que el programador tiene el control para decidir cuándo se suspende y reanuda.

2 - ¿Cuál es la importancia de la suspensión en las coroutines y cómo se implementa?

* La suspensión en las coroutines de Android se refiere a la capacidad de suspender momentáneamente la
ejecución de una coroutine sin obstruir el main thread. La suspensión se implementa utilizando puntos de suspensión explícitos en el código de la coroutine.

3 - ¿Cuál es el propósito del Dispatcher en las coroutines y cómo se elige uno adecuado para cada tarea?

* Especificar en qué hilo (o hilos) se ejecutará una coroutine. La elección del Dispatcher adecuado depende del tipo de tarea y de sus requisitos, ya sea para operaciones I/O o para tareas intensivas.

4 - ¿Cuál es el propósito y el uso de la función async en las coroutines?

* Para lanzar coroutines de manera asíncrona; y es útil cuando sedeben ejecutar tareas concurrentes y 
combinar los resultados 