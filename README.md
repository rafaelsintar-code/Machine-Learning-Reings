# Machine-Learning-Reings
  Proyecto de Machine-Learning usando Neuronal-Network para resolver una partida de Reings generica y aleatoria usando aprendizaje

  Reings es un videojuego de cartas de 1 solo jugador donde el objetivo final es tener los suficientes puntos de atributos
como para jugar la carta de FIN al final de la partida.

 En este juego el jugador tiene 4 atributos que empiezan en un valor de 5 y pueden llegar hasta 10 o 0,
si cualquiera de los atributos llega a su valor maximo o minimo la partida acaba en derrota; cada turno al jugador
se le ofrece una carta con la posibilidad de rechazarla o aceptarla, cualquiera sea la eleccion los puntos de 
atributo seran disminuidos o aumentados dependiendo del proposito de la carta, sin embargo el jugador no
conocera en cuentos puentos aumenta o disminuye cada atributo hasta que la acepte o rechaze, pero si sabra a que atributos afecta,
el juego se gana al llegar a la carta 100 y jugarla sin perder, la dificultad se encuentra en que la carta 100 restara 5 puntos a todos los atributos,
por lo que el jugador debe haberse asegurado de hacer una buena gestion de estos durante la partida o perdera si no
puede aceptar la carta 100; existen ciertas cartas que solo aparecen si se ha aceptado o rechazado una carta especifica anteriormente,
tambien existen cartas que te haran perder grandes valores de atributos si se acepto o no se acepto alguna carta especifca en turnos anteriores.

 El juego cuenta con una BD de 200 cartas con sus propiedades fijas, cada turno hasta el 99 a la maquina se le enseñara una carta y tendra
la opcion de rechazarla o aceptarla y co ello cambiar los valores de sus 4 atributos, al no conocer las variaciones que provoca cada carta tendra que memorizar
no solo las cambios de atributos sino las consecuencias que tiene aceptar o no ciertas cartas.Para este proyecto se utilizara aprendizaje por refuerzo, se usara como estimulos positivos el mantener valores de atributos cercanos a 6 y como estimulos negativos el aceptar cartas que provocan consecuencias negativas mas adelante o el no aceptar la carta FIN.
