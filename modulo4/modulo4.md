## `Brujula al Norte`

- ¿Qué es?

Esta simple brújula te mostrará en qué dirección está el norte.

- Cómo funciona

Este micro:bit tiene un sensor de brújula llamado magnetómetro que mide campos magnéticos. Puede detectar el campo magnético de la tierra y, por lo tanto, puede ser usado como brújula.
Cuando usas la brújula micro:bit por primera vez tienes que calibrarla. Aparecerá un pequeño juego en la pantalla donde tienes que inclinar el micro:bit para encender cada LED, y con esto estará todo listo.
El programa utiliza un bucle infinito (que no acaba nunca) para tomar lecturas de la brújula contínuamente, y las almacena en una variable llamada "bearing" (en inglés, "rumbo"). A continuación utiliza selección: una instrucción si… entonces se encarga de que se muestre N (de norte) en la pantalla LED si el ángulo es mayor que (>) 315 grados o menor que (<) 45. Esto significa que te mostrará dónde está el norte siempre que el micro:bit apunte aproximadamente en la dirección correcta.

![image](https://user-images.githubusercontent.com/114906861/206139352-5a289b52-2ed0-4a18-8d73-7aba3a06c509.png)
- [Archivo](https://github.com/LarryWestbrook/Microbit/blob/main/microbit-compass.hex)

- Mejórado

Haz la brújula más precisa reduciendo el rango del ángulo: haz que el número 45 sea más pequeño y el 315 más grande.
Agrega más puntos cardinales para mostrar cuando el micro:bit apunte hacia el este, el oeste o el sur.
Agrega sonido para que haga ruido al apuntar hacia el norte, de modo que alguien con discapacidad visual pueda también usar la brújula.

![image](https://user-images.githubusercontent.com/114906861/207558659-e1d7ffe8-e15a-446a-aca5-0ac8aacd4c32.png)
- [Archivo](https://github.com/LarryWestbrook/Microbit/blob/main/microbit-PROYECTO-FINAL%20(1).hex)
- [MakeCode](https://makecode.microbit.org/#editor)
