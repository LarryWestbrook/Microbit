# `Ejercicio 1`

Para crea una variable y programar la placa Micro:bit para que, al presionar el botón B, la variable aumente y, al presionar el botón A, la variable disminuya,
deberemos seguir los siguientes pasos:

A continuación, se detallan los pasos a seguir para resolver la actividad 1:

1. Para utilizar una variable, comenzamos por crearla haciendo clic en el botón “Crear variable”.
2. Una vez creada, le asignamos un valor inicial en el interior del bloque “al iniciar”, utilizando el bloque “establecer variable para”. Asignaremos un valor inicial de, por ejemplo, 3.
3. A continuación, utilizaremos los bloques de entrada para programar el
cambio de la variable al presionar los botones A y B. Realizaremos estos
cambios utilizando los bloques “cambiar variable por”, sumando 1 al
presionar botón B, y sumando -1 al presionar el botón A.
4. Por último, no debemos olvidar mostrar la variable en la pantalla de la placa. Para hacerlo de manera continua, colocaremos el bloque “mostrar número” en el interior del bloque “para siempre”.
 
![image](https://user-images.githubusercontent.com/114906861/206123329-64542d08-3b8b-4dea-b8e4-2f0cc1a12309.PNG)
- [Make Code](https://makecode.microbit.org/#editor)
- [Archivo Microbit](https://github.com/LarryWestbrook/Microbit/blob/main/microbit-proyecto%20(1).hex) 

## `Ejercicio 1 Ampliacion`

Para hacer que el cambio de la variable sea continuo, lo incluimos en el bloque“para siempre” con una condición: si el botón A está presionado, cambiamos la
variable en -1. De igual modo, si el botón B está presionado, cambiamos la variable
en 1 unidad. En caso contrario, no modificamos la variable.
A continuación, se detallan los pasos a seguir para resolver la ampliación:
1. Al ejecutar el programa en la placa o en el simulador, observamos que el
valor de la variable no cambia de manera continua: al mantener el botón
presionado, la variable se mantiene estable, y es necesario soltarlo y volver
a presionarlo para que su valor siga cambiando.
2. Para hacer que el cambio de la variable sea continuo, lo incluimos en el
bloque “para siempre” con una condición: si el botón A está presionado,
cambiamos la variable en -1. De igual modo, si el botón B está presionado,
cambiamos la variable en 1 unidad. En caso contrario, no modificamos la
variable.

![image](https://user-images.githubusercontent.com/114906861/206127137-8470607b-74b5-43db-ab4b-460b32f1b613.png)
- [Make Code](https://makecode.microbit.org/#editor)
- [Archivo Microbit](https://github.com/LarryWestbrook/Microbit/blob/main/microbit-proyecto%20(1).hex)

# `Ejercicio 2`

Para crear una imagen grande y programar la placa para que inicialmente se
muestre la parte central de la imagen y, al presionar los botones A y B, la imagen
se deslice a la izquierda o a la derecha, respectivamente, deberás seguir los
siguientes pasos:
Para comenzar, descomponemos la actividad en retos sencillos. Existen muchas
posibilidades, una de ellas sería:
a) Crear la imagen y almacenarla en una variable.
b) Crear una variable con la que mover la imagen dándole valores
ascendientes o descendientes, en función de si se presionan los
botones.
c) Mostrar la imagen en la pantalla de la placa.
Continuamos con el reconocimiento de patrones:
Al comenzar el programa, debemos crear la imagen y dar el valor inicial a
una variable que indicará la posición de la imagen.
A la hora de pensar en la creación de esta variable la cual vamos a
incrementar o disminuir al presionar los botones observamos que
utilizaremos los mismos bloques que usamos en la actividad anterior, por
lo que ya tenemos en mente el algoritmo a usar:
● Creamos la imagen y la variable (en nuestro caso, la llamaremos offset)
● Si se presiona el botón A, mover la imagen a la izquierda (es decir,
modificar el valor de offset, disminuyéndolo para que la imagen se mueva
a la izquierda).
● Si se presiona el botón B, mover la imagen a la derecha (aumentando el
valor de offset).
● Por último, representar la imagen en la posición indicada por el offset.
En cuanto a la abstracción, analizando los demás retos podemos utilizar algunos
de los conocimientos adquiridos durante los módulos 1 y 2 del curso:
●Bloques de variable para calcular el movimiento de la imagen y para
almacenar la imagen grande.
●Bloques de imágenes para crear una imagen grande y para representarla,
controlando la posición (intervalo).
Con lo que debemos descartar el uso del resto de bloques aprendidos hasta
ahora, como los bloques de música o bucles.
Para terminar, codificamos, es decir, utilizamos los bloques para construir
nuestro programa. Replicaremos el programa de la actividad 1 para calcular la
variable “offset” (el intervalo). Además, crearemos una imagen grande, la
almacenaremos en una variable y la representaremos (de manera continua, en el
bloque “para siempre”) con el intervalo calculado.
El programa quedaría como se muestra a continuación:

![image](https://user-images.githubusercontent.com/114906861/206131767-daacb75e-a465-49ff-90af-2331504afe79.png)
- [Make Code](https://makecode.microbit.org/#editor)
- [Archivo Microbit]
