# Credit Card Fraud
Proyecto personal

Para las compañías de tarjetas de créditos es importante poder reconocer las transacciones fraudulentas para así evitar problemas legales, perdidas económicas y perdida de confianza de sus usuarios. En septiembre de 2013 durante dos días se tomaron datos de transacciones realizadas por titulares europeos. En estos dos días ocurrieron 492 fraudes de un total de 284.807 transacciones.
Por temas de confidencialidad no conocemos las características originales ni información a fondo de los datos. Los datos que tenemos se obtuvieron de una transformación PCA. En nuestro caso se obtuvieron 28 componentes, llamadas $V_1,V_2,\cdot,V_{28}$. Aparte de las variables obtenidas por el PCA se tiene la variable Time que mide la diferencia de tiempo en segundos desde la primera transacción, la variable Amount que mide la cantidad de dinero transferido y la variable binaria Class que toma el valor 1 si el dato corresponde a un fraude y 0 sino.

Por lo tanto nuestro interes es la creación de un modelo predictivo con una alta precisión que nos permita poder hacer un seguimiento de las posibles transacciones fraudulentas. 

En el archivo __Rellenar__ crearemos una red neuronal artificial utilizando Keras.
En el archivo __Rellenar__ crearemos una red neuronal artificial utilizando Tensorflow 2.0
