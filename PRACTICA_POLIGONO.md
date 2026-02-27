# PRACTICA POLIGONO
1. Preparar la mesa de trabajo
Lo primero que hace el script es limpiar la zona. Si antes habías intentado hacer un círculo o un cuadrado, el código saca la "escoba" y borra todo lo que hay en la pantalla. Así, cada vez que lo inicias, empiezas con un lienzo totalmente vacío y limpio.

2. Crear el "Nombre" y el "Cuerpo"
En Blender, para que algo exista, primero necesitas darle un nombre (como "MiPolígono") y crear un contenedor vacío. Imagina que sacas una caja etiquetada de un estante; todavía no hay nada dentro, pero la caja ya ocupa un lugar en tu lista de objetos.

3. Marcar los puntos en el suelo (Vértices)
Aquí es donde el código decide dónde poner las esquinas de la figura. Imagina que tienes un compás:

* El código elige un centro.
* Se mueve una distancia fija (el radio) hacia afuera.
* Va poniendo "puntos de plastilina" en el suelo uno por uno.
* Para que queden perfectos, el código calcula el espacio exacto entre cada punto para que den la vuelta completa al círculo sin amontonarse.

4. Unir los puntos con hilos (Aristas)
Ahora que tienes los puntos de plastilina en el suelo, necesitas unirlos para formar la figura. El código actúa como un costurero:

* Toma un hilo y une el Punto 1 con el Punto 2.
* Luego el 2 con el 3, y así sucesivamente.

El paso clave: Cuando llega al último punto, el código sabe que no debe quedarse ahí, sino que lanza el hilo de regreso al Punto 1 para cerrar la figura. Si no hiciera esto, tendrías una línea en zigzag, pero no un polígono cerrado.

5. Mostrarlo en la pantalla
Finalmente, el código le dice a Blender: "Ya terminé de calcular dónde van los puntos y cómo se conectan los hilos, ahora dibújalos de verdad en la vista 3D". En ese momento, la figura aparece mágicamente en tu pantalla.

![POLIGONO (1)](https://github.com/user-attachments/assets/70e5f669-063b-4e01-92f2-6b54481f47a2)

