Ya hemos visto que son las redes neuronales y que las conforman. Ahora veamos **como funcionan**: 

Las **redes neuronales** funcionan mediante un proceso de aprendizaje, donde se ajustan **los pesos** de las conexiones entre las neuronas para producir **salidas deseadas** a partir de entradas dadas

Desglosemos los pasos:

**1. Inicialización de pesos:** Los pesos de las conexiones entre las neuronas se inicializan aleatoriamente o con valores predefinidos.

**2. Paso hacia adelante(Forward propagation):** Durante esta etapa, los datos de entrada se propagan a través de la red neuronal desde la capa de entrada hasta la capa de salida. En cada neurona, se realiza una suma ponderada de las entradas multiplicadas por los pesos y se aplica una función de activación para determinar la salida de la neurona.


**3.Cálculo de la pérdida (Loss calculation):** Una vez que la red neuronal produce una salida, se calcula la diferencia entre la salida predicha y la salida real utilizando una función de pérdida

**4. Retropropagación del error (Backpropagation):** En esta etapa, el algoritmo de optimización calcula la derivada de la función de pérdida con respecto a los pesos de la red neuronal. Esta derivada indica cómo deben ajustarse los pesos para minimizar la pérdida.

**5.Actualización de pesos:** Utilizando la información obtenida en la retropropagación, se actualizan los pesos de la red neuronal para reducir la pérdida. Este proceso se repite iterativamente durante varias épocas de entrenamiento hasta que la red neuronal converge a una solución óptima

![redes-neuronales](https://github.com/ManuelMorenoNeria/NeuralNetworks/assets/114908218/8920a051-1826-4185-a2eb-27cf05ccbb6a)
