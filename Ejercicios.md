# Deep Learning - 2022 - Ejercicios

## Clase 1

1. Resolver el problema de la XOR con 3 neuronas:

    * Implementar SGD para resolver la XOR.
    * ¿Cuántos parámetros desconocidos tiene el modelo?
    * ¿Cuáles son los hiper-parámetros del modelo? Explicar que pasa cuando se varía el learning rate.
    * Una vez entrenado el modelo, realizar predicciones para verificar el funcionamiento.


## Clase 2

1. Stochastic Gradient Descent para encontrar el máximo de una función

    * Implementar en Python un algoritmo basado en Stochastic Gradient Descent para encontrar numéricamente el mínimo de $y = -(x-2)^2 + 3$.   ¿Cuál es el máximo valor que encontró el algoritmo y para qué valor de x? ¿En qué momento detuviste la búsqueda y por qué? ¿Cómo inicializamos los valores random del algoritmo y cómo afectan la convergencia? ¿Cuáles son los hiper parámetros del algoritmo?

2. Mini-Batch Gradient Descent para entrenar un modelo cuadrático

    * Crear un dataset sintético con 10,000 muestras a partir de la siguiente expresión (donde “x” es la feature que toma valores entre 0 y 4, e “y” es la salida):

        $y = -(x-2)^2 + 3 + 0.2 * sin(16*x)$
    
    * Suponer que se tiene un modelo, tal que la relación entre la salida y la entrada está dada por la ecuación presentada a continuación. Suponiendo que se va a utilizar mini-batch SGD para encontrar los valores óptimos de los pesos w1, w2 y w3 tal que minimizan el ECM (Error Cuadrático Medio) (el ECM es la función de costo para este problema), ¿cuál sería la regla de actualización de cada parámetro?. Implementar el algoritmo en Python (usar mini-batch), encontrar los valores óptimos para w1, w2 y w3 y reportar la evolución del ECM con el número de epochs.   

        $\hat{y} =w_1*x^2+w-2*x+w_3$

## Clase 3

1. Red Neuronal Feed Forward en PyTorch

    * Resolver el ejercicio 2 de la Clase 2 utilizando una red neuronal feed forward en PyTorch. Pueden usar los notebooks de la clase de referencia.