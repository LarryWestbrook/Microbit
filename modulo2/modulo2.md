# `Ejercico 1`

A continuación, detallamos los pasos a seguir para que la placa muestre un
cuadrado al agitar la placa:
Si “agitado”
 mostrar icono (cuadrado)
Para completar la actividad nos proponen que esta vez al agítala muestre un
cuadrado girado:

![image](https://user-images.githubusercontent.com/114906861/205583122-6854baab-d6a5-40d5-a8ef-287ec9f3e0d1.png)
- [Make Code](https://makecode.microbit.org/#editor)
- [Archivo Microbit](https://github.com/LarryWestbrook/Microbit/blob/main/microbit-modulos%20(1).hex)

# `Ejecicio 2` 

A continuación, detallamos los pasos a seguir para ampliar la programación y
convertir nuestra animación en un dado.
Para ello debemos añadir a continuación de la animación del dado que nos
muestre en pantalla un número aleatorio entre el 1 y el 6:
El conjunto de bloques sería el siguiente:
Si “agitado:
mostrar icono (cuadrado)
mostrar icono (rombo)
mostrar icono (cuadrado)
mostrar icono (rombo)
mostrar número “escoger al azar de 1 a 6”

![image](https://user-images.githubusercontent.com/114906861/205584621-56510682-3e73-4f8b-a997-d322a9a9f063.png)
- [Make Code](https://makecode.microbit.org/#editor)
- [Archivo Microbit](https://github.com/LarryWestbrook/Microbit/blob/main/microbit-modulos%20(2).hex)


# `Ejercicio 3`

Como último ejercicio, se nos pide que toquemos en la placa la primera parte de
una melodía al presionar el botón A.
Para completar la actividad, primero trasladaremos la primera parte del
pentagrama a notas:

LA MI FA SOL FA MI RE RE FA LA SOL FA MI MI FA SOL LA RE RE
A continuación, programaremos en la placa para que al presionar el botón suene
la melodía programando tono a tono teniendo en cuenta de su se trata de un tono
de un pulso, de medio pulso o de dos pulsos:

Al presionarse el botón A:

reproducir tono La medio por 1 pulso
reproducir tono Mi medio por ½ pulso
reproducir tono Fa medio por 1½ pulso
reproducir tono Sol medio por 1 pulso
reproducir tono Fa medio por ½ pulso
reproducir tono Mi medio por ½ pulso
reproducir tono Re medio por 1 pulso
reproducir tono Re medio por ½ pulso
reproducir tono Fa medio por ½ pulso
reproducir tono La medio por 1 pulso
reproducir tono Sol medio por ½ pulso
reproducir tono Fa medio por ½ pulso
reproducir tono Mi medio por 1 pulso
reproducir tono Mi medio por ½ pulso
reproducir tono Fa medio por ½ pulso
reproducir tono Sol medio por 1 pulso
reproducir tono La medio por 1 pulso
reproducir tono Re medio por 1 pulso
reproducir tono Re medio por 2 pulso

Para modificar la velocidad de la melodía haremos que al agitar la placa el tiempo
cambie a 100 bpm y que al pulsar el botón A+B el tiempo cambie a 50 bpm.
Si “agitado”
cambiar tempo en (bpm) 100

Al presionarse el botón “A+B”
cambiar tempo en (bpm) 50

Para finalizar, programamos la segunda parte de la melodía al pulsar el botón B.
¡Ojo!, esta parte tiene algunas notas altas y otras con bemoles, que es la nota
menos medio tono y es lo mismo que la nota anterior con un sostenido (excepto
en los casos de Do a Si y de Mi a Fa) :

Al presionarse el botón B:
reproducir tono Sol medio por 1 pulso
reproducir tono La# medio por ½ pulso
reproducir tono Re alto por ½ pulso
reproducir tono Do alto medio por ½ pulso
reproducir tono La# medio por ½ pulso 
reproducir tono La medio por 1 pulso

![image](https://user-images.githubusercontent.com/114906861/205589940-2a2c6d44-4e01-4320-b590-0518caa13cc8.png)
- [Make Code](https://makecode.microbit.org/#editor)
- [Archivo Microbit](https://github.com/LarryWestbrook/Microbit/blob/main/microbit-modulos%20(3).hex)
