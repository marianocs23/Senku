# Senku
El siguiente código presenta el juego Senku en lenguaje de C++14.
Se juega con un tablero con diferentes formas según el modelo o el lugar de origen.
Al inicio del juego están todos los espacios ocupados, excepto por uno.El jugador 
debe moveruna pieza por vez. Las piezas sólo pueden moverse capturando mediante 
un "salto" sobre otra, como en las damas. Sólo se puede capturar en horizontal o en 
vertical, nunca en diagonal. Así, al principio, sólo pocas tienen posibilidad de moverse, 
capturando una.El objetivo del juego es eliminar todas las piezas, dejando sólo una en el tablero

Instalacion:
El juego inicia con un panel en el cual escogeras la forma del juego cual te resulte mejor conveniente
por ejemplo:

Senku_Menu:
-----------------------
1.Estilo frances
2.Estilo aleman
-----------------------
Escoger estilo: 1
  1    2    3    4    5    6    7
1           O----O----O
            |    |    |
2           O----O----O
            |    |    |
3 O----O----O----O----O----O----O
  |    |    |    |    |    |    |
4 O----O----O----+----O----O----O
  |    |    |    |    |    |    |
5 O----O----O----O----O----O----O
            |    |    |
6           O----O----O
            |    |    |
7           O----O----O
