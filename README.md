# Tarea4

1 Pregunta:

Para esta parte se crea la función seno con bas en la frecuencia dada y la cantidad de puntos de muestreo que se quieren,
esto para que cuando se lea el archivo de 'bits10k' se pueda crear la señal modulada que se requiere. Esta señal modulada
esta compuesta por un -seno cunado lee un 0, y un seno cuando lee un 1.

2 Pregunta:

Para calcular la potencia promedio primero es necesario calcular la potencia instantánea, que va a ser el cuandrado de la 
señal. Con lo que después se porcede a ahcer una integral trapezoidal de la potencia instantanea en el tiempo, dividido 
entre la cantidad de bits por el periodo.

3 Pregunta:

Ahora se le agrega ruido a la señal modulada, creando primero un linspace que cubra desde los -2 hasta los 3 dB de ruido.
Luego de esto se declara la variable sigma para crear la señal de ruido, que va a ser sumada con la señal modulada.
 
4 Pregunta:

Con la función modulada con ruido creada, se procede a generar la señal espectral de potencia de la señal con el método 
welch, esto antes y depués del canal ruidoso.

5 Pregunta:

Ahora suponiendo que la señal con ruido es una señal que venga de lejos y se ocupa leer, se procede a demodular dicha señal
para volverla a ver como un seno perfecto y leer la información que traiga. Además de esto se contabiliza la cantidad de 
bits que son son diferentes con respecto a la señal original.

6 Pregunta:

Ahora se procede a formar una gráfica entre la relación señal-ruido y la cantidad de errores que se presentan al demodular 
la señal.
