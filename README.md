///--- Manual de usuario ---///

El codigo del juego se encuentra en la carpeta CatchU bajo el nombre de game, los archivos en esta carpeta
son necesarios para el funcionamiento del juego, por lo tanto el codigo se debe correr desde este directorio.

El juego consiste en esquivar los obstaculos que caen por la pantalla para acumular la maxima cantidad de puntos posibles mientras
que aumenta la dificultad a medida que se avanza por los niveles. Mediante los botones "A" para moverse a la izquierda y "D"
para moverse a la derecha podemos controlar al personaje.

Objetos:
- Bananas: Suman un punto al agarrarlas
- Manzanas: Nos dan 1Up (una vida extra)

Obstaculos:
- Bombas
- Cometas
- Fuego

Condiciones de perdida:
- Si tocamos una bomba y no tenemos 1Ups sera Game Over
- Si tocamos un cometa y no tenemos 1Ups sera Game Over
- Si el contador Time llega a 0 antes del nivel 6 sera Game Over
- Si tocamos uno de los fuegos dejados por los cometas sera Game Over independientemente de la cantidad de vidas extra
