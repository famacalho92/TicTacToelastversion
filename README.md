Estructura del proyecto
1. Estructura del Proyecto:

index.jsp: Esta es la página principal donde los usuarios eligen quién comienza el juego (usuario o computadora).
game.jsp: Esta página muestra la cuadrícula del Tic Tac Toe y maneja la interacción del usuario. Utiliza etiquetas JSTL para iterar a través del estado del juego y mostrar el contenido apropiado (imágenes, enlaces).
Cell.java, Line.java, GameBean.java: Estas clases representan la lógica central del juego. Gestionan el estado del juego (X, O o vacío), celdas, líneas y detección del ganador.
EntryServlet.java: Este servlet maneja el envío inicial del formulario donde el usuario elige quién comienza. Establece el jugador inicial en el bean del juego y redirecciona a la página del juego.
GameServlet.java: Este servlet maneja los clics del usuario en la cuadrícula del Tic Tac Toe. Recupera las coordenadas de la celda seleccionada, actualiza el estado del juego, verifica si hay un ganador y redirecciona
 nuevamente a la página del juego.
web.xml: Este descriptor de despliegue configura los servlets y asignaciones para la aplicación web.


Tres en línea (también conocido como Tic-tac-toe, Tateti, OXO, Tres en rayo o La vieja) es un juego de mesa para dos jugadores en el que cada uno 
tiene tres piezas. El objetivo del juego es conseguir que tres de sus piezas estén en línea recta (horizontal, vertical o diagonal) mientras se bloquea al 
otro jugador para que no lo consiga.

Cómo se juega:

Se dibuja un tablero de 3x3 casillas.
Cada jugador elige un símbolo (X o O).
Los jugadores se turnan para colocar su símbolo en una casilla vacía del tablero.
El primer jugador que consigue colocar tres de sus símbolos en línea recta gana el juego.
Si todas las casillas se llenan sin que ningún jugador consiga tres en línea, el juego termina en empate.
Estrategias:

Bloquear al oponente: Es importante no solo intentar colocar tus propias piezas en línea, sino también bloquear al oponente para que no lo consiga.
Pensar a largo plazo: No te concentres solo en el siguiente movimiento, sino en cómo tus movimientos afectarán al juego en general.
Ser creativo: No hay una única forma de ganar en Tres en línea. Explora diferentes estrategias y encuentra la que mejor te funcione.
Tres en línea es un juego simple pero desafiante que puede disfrutarse por personas de todas las edades. Es un juego perfecto para jugar en cualquier momento y en cualquier lugar, 
ya que solo necesita un tablero y dos piezas.

Variantes del juego:

Existen muchas variantes del juego Tres en línea. Algunas de las más populares son:

Cuatro en línea: Se juega en un tablero de 4x4 casillas y el primer jugador que consigue colocar cuatro de sus símbolos en línea recta gana el juego.
Tres en línea con tablero hexagonal: Se juega en un tablero hexagonal y el primer jugador que consigue colocar tres de sus símbolos en línea recta gana el juego.
Tres en línea con piezas móviles: En lugar de colocar las piezas en el tablero, los jugadores las mueven por el tablero para intentar colocarlas en línea recta.
Tres en línea es un juego clásico que ha sido disfrutado por generaciones de personas. Es un juego fácil de aprender pero difícil de dominar, lo que lo convierte en un juego
 perfecto para jugadores de todos los niveles.
![TicTacToe](C:\Users\MAO\Desktop/readme.png)