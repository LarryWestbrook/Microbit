## `Brujula al Norte`

- ¿Qué es?
Esta simple brújula te mostrará en qué dirección está el norte.

- Cómo funciona
Este micro:bit tiene un sensor de brújula llamado magnetómetro que mide campos magnéticos. Puede detectar el campo magnético de la tierra y, por lo tanto, puede ser usado como brújula.
Cuando usas la brújula micro:bit por primera vez tienes que calibrarla. Aparecerá un pequeño juego en la pantalla donde tienes que inclinar el micro:bit para encender cada LED, y con esto estará todo listo.
El programa utiliza un bucle infinito (que no acaba nunca) para tomar lecturas de la brújula contínuamente, y las almacena en una variable llamada "bearing" (en inglés, "rumbo"). A continuación utiliza selección: una instrucción si… entonces se encarga de que se muestre N (de norte) en la pantalla LED si el ángulo es mayor que (>) 315 grados o menor que (<) 45. Esto significa que te mostrará dónde está el norte siempre que el micro:bit apunte aproximadamente en la dirección correcta.

![image](file:///home/asir/Im%C3%A1genes/Capturas%20de%20pantalla/Captura%20desde%202022-12-07%2010-12-48.png)
- [Archivo]
