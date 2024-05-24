Retropropagación del Error (Backpropagation):
La retropropagación del error es un proceso crucial en el entrenamiento de redes neuronales. Aquí se describe paso a paso cómo funciona:

Cálculo de la Derivada de la Función de Pérdida:

El primer paso en la retropropagación es calcular la derivada (o gradiente) de la función de pérdida con respecto a cada peso en la red neuronal. Esta derivada indica la dirección y magnitud del cambio necesario en los pesos para reducir la pérdida.
Propagación hacia Atrás:

Utilizando la regla de la cadena, la derivada de la pérdida se transmite desde la capa de salida hacia la capa de entrada. Esto significa calcular las derivadas parciales de la pérdida con respecto a los pesos en cada capa, comenzando desde la última capa (salida) y avanzando hacia la primera capa (entrada).
Cálculo de Gradientes en Cada Capa:

En cada capa, se calculan los gradientes de los pesos y los sesgos (bias). Esto se hace multiplicando el gradiente de la capa siguiente por la derivada de la función de activación de la neurona actual.
Actualización de Pesos:


Una vez que se tienen todos los gradientes, se actualizan los pesos de la red utilizando un algoritmo de optimización. El más común es el descenso de gradiente, que ajusta los pesos en la dirección opuesta al gradiente de la pérdida, multiplicado por una tasa de aprendizaje. La fórmula general para actualizar un peso 


Iteración y Convergencia:

Este proceso se repite iterativamente para múltiples épocas (iterations) hasta que la función de pérdida alcanza un valor mínimo aceptable, lo que indica que la red ha aprendido a hacer predicciones precisas.
