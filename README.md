# Ejercicio de hilos de java
En este ejercicio haremos uso de la clase thread para crear hilos en java
## Enunciado del Ejercicio:

- Crea una clase llamada MiHilo que extienda de la clase Thread.
- Dentro de MiHilo, sobrescribe el método run() para que imprima un mensaje en consola. Por ejemplo, que muestre el nombre del hilo y un contador.
- En una clase principal, crea e inicia tres instancias de MiHilo. Observa cómo se ejecutan de manera concurrente.

- Asegúrate de que cada hilo muestre un mensaje que permita identificarlo, como "Hilo 1", "Hilo 2" y "Hilo 3".

## Instrucciones Detalladas:

- En la clase MiHilo, dentro del método run(), implementa un bucle que itere una cierta cantidad de veces (por ejemplo, 10 veces) y en cada iteración, imprime el nombre del hilo y el número de iteración.
- En la clase principal, crea tres objetos de MiHilo, asigna un nombre a cada hilo utilizando el constructor de la clase Thread o el método setName().
- Inicia cada hilo con el método start().
- Observa la salida en la consola y discute con tus compañeros acerca de la naturaleza concurrente de la ejecución de los hilos.
