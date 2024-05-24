### Explicación Detallada
#### Retropropagación del Error (Backpropagation):

La retropropagación del error es un proceso crucial en el entrenamiento de redes neuronales. Aquí se describe paso a paso cómo funciona:

1. **Cálculo de la Derivada de la Función de Pérdida**: 
   - El primer paso en la retropropagación es calcular la derivada (o gradiente) de la función de pérdida con respecto a cada peso en la red neuronal. Esta derivada indica la dirección y magnitud del cambio necesario en los pesos para reducir la pérdida.

2. **Cálculo de Derivadas en la Capa de Salida**:
   - Primero, se calcula cómo la pérdida cambia con respecto a los pesos en la capa de salida.

3. **Propagación de Derivadas hacia Atrás**:
   - Luego, estas derivadas se utilizan para calcular cómo la pérdida cambia con respecto a los pesos en la capa anterior, y así sucesivamente, hasta llegar a la capa de entrada. Este proceso se realiza capa por capa, desde la última capa (salida) hasta la primera capa (entrada).

4. **Cálculo de Gradientes en Cada Capa**:
   - En cada capa, se calculan los gradientes de los pesos y los sesgos (bias). Esto se hace multiplicando el gradiente de la capa siguiente por la derivada de la función de activación de la neurona actual.

5. **Actualización de Pesos**:
   - Una vez que se tienen todos los gradientes, se actualizan los pesos de la red utilizando un algoritmo de optimización. El más común es el descenso de gradiente, que ajusta los pesos en la dirección opuesta al gradiente de la pérdida, multiplicado por una tasa de aprendizaje.
     
6. **Iteración y Convergencia**:
   - Este proceso se repite  para múltiples épocas  hasta que la función de pérdida alcanza un valor mínimo aceptable, lo que indica que la red ha aprendido a hacer predicciones precisas.

![maxresdefault](https://github.com/ManuelMorenoNeria/NeuralNetworks/assets/114908218/a13ee79a-395a-45f2-8d11-5a7861b33524)
