

## REAL TIME STRATEGY GAME

La idea del proyecto es programar un video juego de estrategia estilo RTS (estrategia en tiempo real) ambientado en la antigüedad, 
el cual estará inspirado en varios juegos del mismo estilo (Starcraft, Warcraft, Command and Conquer, Total War, Stronghold, Cossacks, etc.),
aunque principalmente en las mecánicas del Age of Empires 2 con todas sus versiones y expansiones.
Damos una breve explicación sobre la diferencia con los TBS (estrategia por turnos), y su principal contraste se basa en cómo fluye el tiempo.
Si a los jugadores se les asigna individualmente un espacio de tiempo en el cual solo uno de ellos puede manejar y preparar su estrategia a la vez, 
entonces estamos ante un juego de estrategia por turnos. Dicho en otras palabras, se le asemeja a un juego de mesa digital en términos prácticos. 
Por otro lado, en los RTS, todas las acciones suceden al mismo tiempo, por lo que la velocidad y la adaptación son los principales factores para obtener la victoria. 
Podríamos decir que simulan lo que sucedió desde el comienzo de las civilizaciones, donde nadie tuvo que esperar un turno,
sino que todas se desarrollaron en el mismo espacio de tiempo, aunque la demora en el desarrollo no fuera el mismo. Esto es lo que sucede en un RTS,
todos los jugadores comienzan de la misma forma y no hay pausas en sus desarrollos.

La siguiente explicación sobre el funcionamiento de un RTS detalla en gran medida cómo será el proyecto terminado. 

Primeramente, podemos abordar los dos grandes bloques con los que la gran mayoría de los RTS están compuestos:el económico y el militar.

Bloque económico
En este bloque el jugador necesita recoger recursos necesarios para la creación y formación de ejércitos que comandará para derrotar al enemigo. 
Esto, a su vez, debe subdividirse en dos partes: los distintos tipos de recursos junto con sus usos; y cómo se los recolecta. 
Los tipos de recursos que existan en un RTS generalmente determinan el realismo del mismo. Por dar un ejemplo, tenemos por un lado Planetary Annihilation en donde 
solamente existen dos recursos, metal y energía, mientras que en Stronghold se pueden obtener más de 20 recursos, incluyendo cerveza, muebles, sedas, especias, etc. 
La diferencia está en que el primer tipo de RTS, sus batallas habitualmente son masivas y se liberan en cuestión de minutos de empezar, mientras que en el segundo tipo de RTS,
las partidas pueden durar varias horas hasta conseguir lo necesario para la formación de ejércitos. 
Este proyecto contará con no más de 4 recursos a determinar.
Sobre la recolección de recursos, dependiendo de qué RTS analicemos, el mismo recurso puede ser recogido de distintas fuentes. 
En Age of empires 2, para juntar alimento tenemos distintos tipos de animales los cuales dan alimento más rápido y sin gastar otros recursos,
mientras que también tenemos granjas y trampas para peces las cuales necesitan madera y otorgan alimento de forma casi ilimitada con la mecánica de replantación.
En otros RTS, la eficiencia se ve en el tipo de alimento que se obtenga, haciendo diferencia entre carnes y cereales, maderas livianas y pesadas, etc. 
De momento, siendo que el proyecto tenderá al minimalismo en todos sus aspectos, no se contarán con distintas fuentes de recolección para el mismo recurso, 
aunque no se descarta enteramente, y la unidad económica será multifuncional, pudiendo recolectar todo tipo de recursos.

Bloque Militar
Este bloque debe poder ser de dos formas: ofensivo y defensivo. Cuando se habla de ofensa en un RTS nos referimos al ataque, a unidades que se especialicen en atacar. 
Las unidades pueden ser terrestres, aéreas o acuáticas (en nuestro proyecto por ahora sólo serán terrestres), de ataque cuerpo a cuerpo o a distancia. 
Cada unidad puede tener diferentes características, las cuales se pueden categorizar en ataque, armadura, HP (puntos de energía) 
y si su ataque es a distancia también se determina cuánto es su alcance y su puntería, entre varios otros aspectos. Con respecto a las mecánicas de las unidades,
también se pueden dividir en dos: aquellas unidades que pueden desempeñarse de forma única dependiendo de las circunstancias 
y contra quién se enfrente (como en el caso de la mayoría de las unidades de Starcraft) o seguir el modelo piedra, papel o tijera. 
Este último modelo se puede entender con un ejemplo de lo que sucede en Age of Empires 2. Los jinetes tienen ventaja sobre milicia, la milicia tiene ventaja sobre lanceros,
los lanceros tienen ventaja sobre jinetes. Esto sucede de forma transversal entre casi todas las unidades de infantería, arquería, caballería y asedio. 
En nuestro caso, este será el modelo a seguir.
Con relación a la defensa, esta consiste principalmente de estructuras que otorguen a las unidades militares protección y/o impedir el paso de las unidades 
enemigas hacia un determinado lugar. Murallas, torres, fuertes, bunkers, castillos, algunas maquinarias de asedio las cuales puedan acarrear unidades dentro, 
incluso edificios militarmente neutros pueden llegar a utilizarse como muros.

Tecnologías
Este es un aspecto que puede influir en todos los edificios y unidades del juego. Están las tecnologías que agilizan el proceso económico, 
en donde las unidades pueden contar con mayor capacidad, moverse más rápido o juntar recursos de manera más ágil.
También las hay para aumentar las defensas de distintos edificios y unidades, así como también su ataque y su alcance en los casos pertinentes.
Consumen tiempo y recursos, pero son desarrollos necesarios si el contrincante ha decidido utilizarlos, 
ya que sin ellos contaríamos con una desventaja importante en el momento del conflicto.

Civilizaciones
Aquí entra en juego el delicado balance que tiene que existir entre las distintas civilizaciones que puede elegir el jugador. 
Una sola ventaja demasiada poderosa puede hacer que una civilización sea imposible o demasiado difícil de derrotar.
En la jerga de los juegos esto se denomina OP (Over Powered). 
Sin embargo, estas ventajas son las que definen la jugabilidad de cada civilización y las diferencian del resto, por lo que son necesarias. 
En algunos juegos las diferencias se suelen notar principalmente en solo tres aspectos únicamente asociados a las unidades, las cuales son el tiempo de creación,
los costos de creación y su resiliencia. En estos casos generalmente solo da para la formación de 3 civilizaciones, las cuales tendrán una o dos ventajas de las tres existentes.
Un claro ejemplo es Starcraft con sus tres civilizaciones, Protoss, Zergs y Terrans.

Civilización	Creación	  Costo	   Resiliencia
Protoss	      Lenta	      Alto	   Alta
Terrans	      Normal	    Normal	 Normal
Zergs	        Rápida	    Bajo	   Baja

En otros juegos, sin embargo, el árbol de tecnologías suele estar compartido y las diferencias son más específicas y sutiles, aunque pueden impactar tanto como cualquier
otro modelo de diferenciaciones. Para la creación del proyecto, en una primera instancia solo tendrá una civilización y las diferencias contra el enemigo se manejarán con 
la micro-administración.

Micro-management
En los RTS existen dos tipos de administración o manejo, macro y micro. La principal diferencia está en que la macro asegura la victoria general de la partida, 
teniendo que ver con la estrategia utilizada y la adaptación hacia las circunstancias, mientras que la micro asegura la victoria en enfrentamientos individuales.
En esta parte se tienen en cuenta cómo se responderá al enfrentamiento. Para eso es necesario que las unidades cuenten con varios comandos para que el usuario pueda 
tener un control lo más completo posible sobre éstas. En esto se incluyen formaciones, estados y comandos de movimientos. 
Las formaciones son útiles para reaccionar ante ataques a distancia o cómo enfrentar la situación, y pueden ser en línea, escalonada, de flancos, circulares, cuadradas, 
aleatorias, etc. Los estados pueden ser ofensivos (la unidad reacciona contra otra cuando ésta esté en su línea de persecución y la perseguirá mientras siga en esta línea), 
defensivos (la unidad reacciona contra otra cuando ésta esté en su línea persecución y la perseguirá hasta cierta distancia para luego volver a su posición original), 
mantener posición (sólo atacará si la unidad enemiga está dentro del alcance de ataque, aunque no se moverá de donde está) y pacífico (no se moverá ni atacará). 
Los comandos de movimientos pueden ser patrullar (seleccionados dos puntos del mapa, las unidades se moverán indefinidamente dentro de esos límites), 
proteger (las unidades estarán cerca de la unidad a proteger), seguir (las unidades estarán lo más lejos posible de la unidad a seguir, dentro de su línea de visión) 
o simplemente ordenar a la unidad que se traslade a cualquier punto del mapa. Todos los comandos de movimiento estarán determinados por la formación y
el estado en el cual se encuentre la unidad. No será lo mismo enfrentarse a un ejército ordenándoles a todas nuestras unidades que ataque a una sola unidad enemiga, 
que hacer que nuestro ejército patrulle hacia las unidades enemigas, haciendo que ataque a todas las unidades del frente.
Otra gran ayuda son los iconos de formación de grupos, los cuales con una sola tecla se selecciona automáticamente un número de unidades predefinido por el usuario.
La rapidez en el manejo de distintos grupos en un enfrentamiento puede ser clave para ganarlo. 
De esta forma, la micro dependerá de cuán hábil sea el jugador para manejar a sus tropas en cada enfrentamiento.
 
