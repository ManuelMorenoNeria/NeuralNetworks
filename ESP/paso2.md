Como hemos visto anteriormente, una red neuronal esta formada por los siguientes elementos:

- Inputs

- Pesos

- Sesgos

- Suma Ponderada

- Funcion de activacion


![51549981077_3a7a520c81_b](https://github.com/ManuelMorenoNeria/NeuralNetworks/assets/114908218/da85bd68-1a55-49ce-ab79-272db89f3b5e)

Estos elementos funcionan de la siguiente manera:

  1. Multiplicamos los parametros de entrada por los pesos de la primera capa

  2. Sumamos el sesgo al producto de la multiplicacion

  3. Al resultado anterior se le aplica la funcion de activacion de la siguiente capa:
     
       Las funciones de activación permiten que una red neuronal aprenda relaciones más complejas y flexibles entre los datos de entrada y la salida, no limitándose a relaciones lineales simples (como una línea recta). En lugar de tratar de ajustar los datos a una relación estricta y directa, como lo haría una línea recta, las funciones de activación permiten que la red aprenda y modele relaciones no lineales, como curvas o formas más complejas.
     
  5. Se envia a la capa siguiente el resultado

  6. Repetimos el proceso
