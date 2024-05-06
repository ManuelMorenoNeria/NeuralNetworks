Ya hemos visto que son las redes neuronales y que las conforman. Ahora veamos **como funcionan**: 

Las **redes neuronales** funcionan mediante un proceso de aprendizaje, donde se ajustan **los pesos** de las conexiones entre las neuronas para producir **salidas deseadas** a partir de entradas dadas

Desglosemos los pasos:

**1. Inicialización de pesos:** En esta etapa, los pesos de las conexiones entre las neuronas se establecen inicialmente de forma aleatoria o utilizando valores predefinidos. Estos pesos determinan la fuerza de la conexión entre las neuronas y son esenciales para el funcionamiento de la red neuronal.

**2.Forward propagation:** 
   - Durante la propagación hacia adelante, los datos de entrada se transmiten a través de la red neuronal desde la capa de entrada hasta la capa de salida.
   - Cada neurona en una capa oculta realiza una suma ponderada de las entradas recibidas, multiplicando cada entrada por su peso correspondiente y sumando los resultados. Luego, se agrega un sesgo a esta suma ponderada.
   - El resultado de esta operación se pasa a través de una función de activación, que determina si la neurona debe "activarse" y cuál será su salida.
   - Este proceso se repite para cada capa de la red neuronal hasta llegar a la capa de salida, que produce la predicción final.
     
**3.Cálculo de la pérdida (Loss calculation):**
   - Una vez que la red neuronal ha generado una salida, se calcula la diferencia entre la salida predicha y la salida real utilizando una función de pérdida (loss function). Esta función de pérdida cuantifica qué tan bien está realizando la red neuronal en sus predicciones.
   - El objetivo es minimizar esta función de pérdida, lo que implica ajustar los pesos de la red neuronal para reducir el error entre las salidas predichas y las salidas reales.

**4. Retropropagación del error (Backpropagation):** En esta etapa, el algoritmo de optimización calcula la derivada de la función de pérdida con respecto a los pesos de la red neuronal. Esta derivada indica cómo deben ajustarse los pesos para minimizar la pérdida.
   - En esta etapa, el algoritmo de optimización calcula la derivada de la función de pérdida con respecto a los pesos de la red neuronal. Esta derivada indica cómo deben ajustarse los pesos para minimizar la pérdida.
   - Utilizando la regla de la cadena, esta derivada se propaga hacia atrás a través de la red neuronal, permitiendo calcular la contribución de cada peso a la pérdida total.
   - Con esta información, se actualizan los pesos de la red neuronal utilizando un algoritmo de optimización, como el descenso de gradiente, con el objetivo de reducir la pérdida.
     
**5.Actualización de pesos:** 
   - Utilizando la información obtenida en la retropropagación del error, se actualizan los pesos de la red neuronal para reducir la pérdida. Este proceso se realiza iterativamente durante varias épocas de entrenamiento hasta que la red neuronal converge a una solución óptima.
   - Es importante ajustar la tasa de aprendizaje y otros hiperparámetros para garantizar un entrenamiento eficaz y evitar el sobreajuste.
     
![redes-neuronales](https://github.com/ManuelMorenoNeria/NeuralNetworks/assets/114908218/8920a051-1826-4185-a2eb-27cf05ccbb6a)



Expliquemos mas detalladamente el paso 2:

Como hemos visto anteriormente, una red neuronal esta formada por los siguientes elementos:
- Inputs
- Pesos
- Sesgos
- Suma Ponderada
- Funcion de activacion

Estos elementos funcionan de la siguiente manera:

**1. Multiplicamos los parametros de entrada por los pesos de la primera capa** 

**2. Sumamos el sesgo al producto de la multiplicacion** 

**3. Al resultado anterior se le aplica la funcion de activacion de la siguiente capa:** 

**4. Se envia a la capa siguiente el resultado**

**5. Repetimos el proceso**
