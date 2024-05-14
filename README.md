Estructura del proyecto
1. Estructura del Proyecto:

index.jsp: Esta es la p�gina principal donde los usuarios eligen qui�n comienza el juego (usuario o computadora).
game.jsp: Esta p�gina muestra la cuadr�cula del Tic Tac Toe y maneja la interacci�n del usuario. Utiliza etiquetas JSTL para iterar a trav�s del estado del juego y mostrar el contenido apropiado (im�genes, enlaces).
Cell.java, Line.java, GameBean.java: Estas clases representan la l�gica central del juego. Gestionan el estado del juego (X, O o vac�o), celdas, l�neas y detecci�n del ganador.
EntryServlet.java: Este servlet maneja el env�o inicial del formulario donde el usuario elige qui�n comienza. Establece el jugador inicial en el bean del juego y redirecciona a la p�gina del juego.
GameServlet.java: Este servlet maneja los clics del usuario en la cuadr�cula del Tic Tac Toe. Recupera las coordenadas de la celda seleccionada, actualiza el estado del juego, verifica si hay un ganador y redirecciona
 nuevamente a la p�gina del juego.
web.xml: Este descriptor de despliegue configura los servlets y asignaciones para la aplicaci�n web.


Tres en l�nea (tambi�n conocido como Tic-tac-toe, Tateti, OXO, Tres en rayo o La vieja) es un juego de mesa para dos jugadores en el que cada uno 
tiene tres piezas. El objetivo del juego es conseguir que tres de sus piezas est�n en l�nea recta (horizontal, vertical o diagonal) mientras se bloquea al 
otro jugador para que no lo consiga.

C�mo se juega:

Se dibuja un tablero de 3x3 casillas.
Cada jugador elige un s�mbolo (X o O).
Los jugadores se turnan para colocar su s�mbolo en una casilla vac�a del tablero.
El primer jugador que consigue colocar tres de sus s�mbolos en l�nea recta gana el juego.
Si todas las casillas se llenan sin que ning�n jugador consiga tres en l�nea, el juego termina en empate.
Estrategias:

Bloquear al oponente: Es importante no solo intentar colocar tus propias piezas en l�nea, sino tambi�n bloquear al oponente para que no lo consiga.
Pensar a largo plazo: No te concentres solo en el siguiente movimiento, sino en c�mo tus movimientos afectar�n al juego en general.
Ser creativo: No hay una �nica forma de ganar en Tres en l�nea. Explora diferentes estrategias y encuentra la que mejor te funcione.
Tres en l�nea es un juego simple pero desafiante que puede disfrutarse por personas de todas las edades. Es un juego perfecto para jugar en cualquier momento y en cualquier lugar, 
ya que solo necesita un tablero y dos piezas.

Variantes del juego:

Existen muchas variantes del juego Tres en l�nea. Algunas de las m�s populares son:

Cuatro en l�nea: Se juega en un tablero de 4x4 casillas y el primer jugador que consigue colocar cuatro de sus s�mbolos en l�nea recta gana el juego.
Tres en l�nea con tablero hexagonal: Se juega en un tablero hexagonal y el primer jugador que consigue colocar tres de sus s�mbolos en l�nea recta gana el juego.
Tres en l�nea con piezas m�viles: En lugar de colocar las piezas en el tablero, los jugadores las mueven por el tablero para intentar colocarlas en l�nea recta.
Tres en l�nea es un juego cl�sico que ha sido disfrutado por generaciones de personas. Es un juego f�cil de aprender pero dif�cil de dominar, lo que lo convierte en un juego
 perfecto para jugadores de todos los niveles.
![TicTacToe](C:\Users\MAO\Desktop/readme.png)