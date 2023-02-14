# Descripción

## Descripción general

**Famecraft 3D** es un _eurogame_ online multiplataforma de peso ligero muy *draconiano*, con un **adorable aspecto visual** y una mecánica base de colocación de trabajadores con su propias peculiaridades.

Plantea la premisa de recolectar recursos para gastarlos de forma casi inmediata formando conjuntos y en que las acciones las vas creando a medida que avanza el juego.

**Jugadores/as:**        2 a 5  
**Duración:**           60 minutos  
**Edad:**               14+   
**Género / Mecánicas:** Eurogame - Colocación de distintos tipos de trabajadores  

Cada jugador moveis un único peón en los distintos espacios de acción y en cada uno tendr 2 opciones:

- por un lado, recolectar recursos en función de las cartas que van jugando sobre la localización correspondiente

- o, por otro, completar alguno de los pedidos disponibles en un suministro común, entregando el conjunto de recursos indicado para, principalmente, anotar puntos (aunque muchos proporcionan **recompensas adicionales**).

De esta forma ireis resolviendo turnos recolectando recursos para gastarlos lo más rápidamente posible en esos pedidos (_encantamientos_) para ir acumulando la mayor cantidad de puntos posibles antes de que se detone el final de la partida agotándose alguno de los mazos de cartas.

Con **Famecraft 3D** también tienes algunos **condimentos adicionales**, como _cartas de objetivo personal_ (algunas se pueden resolver durante los turnos y otras ofrecen puntos de victoria al final de la partida), o **que los espacios de acción van evolucionando durante la partida**.

Cuando visitas una **_Tienda_** (espacio de acción) podrás ir colocando tus cartas de **_Dragones Artesanos_** que te proporcionarán doble beneficio:

- uno asociado a la _Tienda_ donde te colocas    

- otro asociado tu propia carta de _Dragón Artesano_     

Tus dragones te proporcionarán recursos adicionales cuando esa tienda vuelva a ser visitada.

Además, al completar **_Encantamientos_** (los pedidos) habrá que visitar una _Tienda_ de tipo coincidente con el encantamiento, de forma que el pedido se solapará sobre la tienda y proporcionará más recursos la próxima vez que sea visitada.

De esta forma los espacios de acción te van proporcionando cada vez más recursos, acelerando el ritmo de la partida por un lado, y alterando el peso de los espacios de acción por otro, haciendo que se vuelvan más interesantes a medida que se van cargando con cartas.

Es un juego bien equilibrado en el que los efectos están pensados para mantener el ritmo sin agobiar pero que obliga a adaptarse, pues los pedidos son comunes y puedes deducir en qué _encantamientos_ están interesados tus contrincantes en función de los recursos que se van acumulando.


## Mecánica

Tendrás un tablero principal con una serie de tiendas asociadas a cada uno de los seis recursos y con espacio para un máximo de 3 dragones artesanos, que también te proporcionan un recurso de los seis posibles.

Tu objetivo es intentar anotar la mayor cantidad de puntos posibles completando encantamientos y cumpliendo los requisitos de dragones selectos.

En cada turno debes desplazar tu peón a una tienda distinta (si estuviese ocupada por otros jugadores deberás recompensar con recursos a los jugadores presentes) y escogerás entre recolectar recursos (uno por símbolo visible) pudiendo activar el efecto de la tienda (si lo tuviese), jugar un dragón (recibiendo una recompensa) y activar un dragón presente, o completar un encantamiento cuyo símbolo coincida con la tienda, devolviendo a la reserva los recursos indicados para obtener las recompensas correspondientes y activar todos los dragones presentes en la tienda.

Si una tienda se completa, debe revelarse una nueva tienda para que siempre haya espacios en los que jugar dragones (que se consiguen de un suministro común).

Al final de cada turno se reponen los dragones y los encantamientos, finalizando la partida cuando se agote uno de estos mazos.


## Objetos del videojuego

Para preservar la belleza de las ilustraciones de Sandara Tang (The Lord of the Rings: The Card Game, Legacy of Dragonholt, Descent: Journeys in the Dark 2nd Edition) en tonos pastel, los escenarios y personajes se implementa en 2D.

Detalle de los objetos del videojuego (GameObjects):

Se implementan los siquientes Objetos del videojuego:

- Escenario de fondo de la ciudad en 2D
- 121 Cartas Pequeñas 3D (Ref. original 44×67 mm):
    - 42 Cartas de Dragón Artesano
    - 36 Cartas de Dragón Selecto
    - 36 Cartas de Encantamiento
    - 7 Cartas de Compañero
- 34 Cartas de Tienda 3D (Ref. original 89×140 mm.):
    - 8 Ayudas de Jugador
    - 6 Marcadores de Jugador (Ref. original textura de madera)
    - 6 Marcadores de Reputación (Ref. original textura de cartón)
    - 24 Monedas (Ref. original textura de cartón)
- 210 Fichas de Producto 3D  (Ref. original textura de cartón):
    - 35 de Pan
    - 35 de Carne
    - 35 de Pociones
    - 35 de Plantas
    - 35 de Hierro
    - 35 de Cristal
- Reglamento (en .pdf | x/html)

**La edición Premium añade o sustituye los siguientes elementos:**

- 6 Marcadores de Dragón 3D (Ref. original textura de plástico)
- 6 Marcadores de Reputación 3D [sustituye] (Ref. original textura de madera)
- Panel de shockets Base de Gametrayz, de Recursos y de monedas (3D)
- 24 Monedas 3D [sustituye] (Ref. original textura de Metal)
- 210 Fichas de Producto [sustituye] (Ref. original textura de Madera)

La pantalla del juego mostrará la situación en el tablero y el jugador podrá hacer zoom + y zoom -
El jugador tendrá botones para mostrar y ocultar las ventanas con sus recursos.
El peón de jugador 3D se irá desplazando de tienda en tienda y el marcador de vida de cada jugador es el que se desplaza por el tablero


## Conceptos básicos

### Las tiendas

Las tiendas son el corazón de la Ciudad y aquellas que emplean Cremallamas son muy apreciadas.

6 escenarios 2D.
En la esquina superior izquierda muestran el icono de uno de los seis tipos de **Recursos** o un efecto particular y en la parte superior derecha el texto con fondo de pergamino.

En la banda inferior encontramos tres espacios para colocar **Dragones Artesanos** con unos determinados tipos y unas recompensas.

Y, opcionalmente, justo encima de estos espacios puede aparecer una banda como efecto asociado a la tienda.
En estos espacios se colocarán los **Dragones Artesanos**.


### Los recursos

Hay 6 tipos de **Recursos**, representados por iconos que están asociados a las tiendas y a los Dragones Artesanos


### El Peón de dragón

Cada jugador dispondrá de un **Peón de Dragon** que irá desplazando entre estas tiendas para activar sus efectos, así como los de los dragones artesanos que se encuentren en ellas. Además el jugador podrá jugar dragones artesanos en ella. Si una tienda ya contiene peones de otros jugadores, el jugador activo deberá asumir una penalización.


### Los Dragones Artesanos

Existe un **dragón artesano** para cada tipo de **recurso**, con un efecto de activación en su banda inferior. Aunque todos los dragones son en apariencia distintos, muestran el mismo efecto si pertenecen a un mismo tipo.

#### Habilidades

Si decides utilizar una habilidad, tienes que resolverla por completo en la medida de lo posible (salvo que la habilidad incluya la expresión *"puedes"*)

#### Asignar Dragones

Cada vez que uses una habilidad para **Asignar** un Dragón Artesano a una tienda, tienes que aplicar todas las reglas de Asignación de Dragones (véase la sección), a menos que el texto de la habilidad indique otra cosa.
Esto significa que el Dragón que Asignes tiene que **coincidir** con el icono del espacio seleccionado (se mostrará un efecto hover cuando se sitúe sobre él) y, después de Asignarlo, obtienes la **recompensa** indicada, también mostrada con una animación de la recompensa a tu panel.

Los Guardallamas comparten un vínculo especioal con los 6 Dragones Artesanos, lo cual inspera sus habilidades únicas:

| Dragón Artesano | Recurso  | Color       | Habilidad                                                                                 |
|-----------------|----------|-------------|-------------------------------------------------------------------------------------------|
| Herrumbre       | Hierro   | Azul marino | Obtén 2 + 1 recurso de esa tienda o de un dragón artesano                                 |
| Perrito         | Carne    | Rojo        | Asigna 1 Dragón Artesano a la Ciudad                                                      |
| Miel            | Pan      | Ámbar       | Roba un Dragón Artesano                                                                   |
| Corajoya        | Cristal  | Cyan        | Obtén 3 recursos diferentes de tu elección                                                |
| Bayas           | Pociones | Morado      | Intercambia este con otro Dragón Artesano en la Cuidad y activa el fuego del nuevo dragón |
| Loto            | Plantas  | Verde       | Regala 1 recurso a otro jugador para obtener 2 vidas                                      |


Los jugadores irán acumulando estos recursos, teniendo un límite de siete unidades de cada tipo (debiendo descartar el exceso al final de cada turno).


### Las Monedas

Funcionan como comodín a la hora de completar encantamientos (aunque solo se podrá sustituir un recurso de cada tipo de los requeridos por el encantamiento por monedas) y proporcionarán puntos al final de la partida.


### Puntos de Victoria

El objetivo principal del juego es el de acumular **Puntos de Victoria**.

Para ello **cada jugador contará con un marcador en forma de corazón** con el color de cada recurso, que irá progresando con el track de puntuación.


### Encantamientos

La vía principal para obtener **puntos de victoria** será completando **Encantamientos**, cada uno de ellos asociados a un tipo de **recurso**.

Estos encantamientos muestran un conjunto de recursos requeridos para completarlos y una recompensa en su banda inferior, consistente en puntos de victoria, monedas y/o dragones (artesanos o selectos).

Para completar encantamientos habrá que visitar una tienda del tipo coincidente, quedando solapado bajo la tienda, proporcionando más recursos en próximas visitas.


### Dragones selectos

Alternativamente tenemos los **Dragones Selectos**, que proporcionarán puntos de victoria cumpliendo ciertos requisitos.

Hay dos tipos de dragones selectos:

- los de puntuación durante la partida (con símbolo de sol)

- y los de puntuación de final de partida (con símbolo de luna).

Un jugador podrá jugar cualquier cantidad de dragones selectos con símbolo de sol durante un mismo turno.


## El tablero de juego

El circuito que sirve de track de puntuación con casillas numeradas del 1 al 50. Este track encierra la zona de encantamientos y dragones selectos, quedando a un lado la zona de suministro de dragones artesanos.



# Inicio de la partida

1. Animación de despliegue del tablero de juego
2. Animación de desplieque las tiendas iniciales con un dragón artesano inicial del tipo coincidente.
3. Animación de despliegue de una reserva general con los recursos.
4. Animación de colocación de las monedas en la fuente.
5. Animación de pliegue que forma el mazo de tiendas con 1 tienda de cada tipo de recurso y 4 tiendas con efectos variados.
    - Animación de barajado de las 10 cartas y de botón de show/hide a un lado.
6. Animación de preparación del mazo de dragones artesanos, devolviendo a la caja 1/2 dragones de cada tipo en partidas de 3/2 jugadores (a 4 se utilizan todos).
    - Animacion de barajado del mazo y colocación en el espacio correspondiente
    - Animación de revelado de las 5 primeras cartas.
7. Animación de barajado del mazo de dragones selectos y
    - animación de colocación en el espacio correspondiente.
8. Opciones de mazo de encantamientos a usar (morado-normal o dorado-avanzado),
    - Animación de mezcla y colocación en el espacio correspondiente,
    - Animación de revelado de los 5 primeros.
9. Panel del jugador. Cada jugador escoge un color y recibe con animaciones:
    - una hoja de referencia,
    - un peón,
    - un marcador de puntuación (que se coloca al comienzo del track),
    - El jugador descarta 3 cartas del mazo de dragones artesanos
    - El jugador roba 2 cartas del mazo de dragones selectos
        - Animación de escoger uno y
        - Animación de devolver el otro al fondo del mazo
10. Animación de escoger aleatoriamente al jugador inicial. En partidas de 4/5 jugadores, el cuarto y quinto jugador toma un recurso a su elección.


# Desarrollo de la partida

Una partida de **Flamecraft** se desarrolla a lo largo de un número indeterminado de turnos alternados por los jugadores, comenzando por el jugador inicial y continuando en el sentido de las agujas del reloj.

En cada turno, el jugador activo debe desplazar su peón de dragón a una tienda distinta de la que ocupaba al comienzo del turno. Si en la tienda de destino hay uno o más peones de dragón de otros jugadores, deberá entregar un recurso a cada uno de esos jugadores (si no tiene recursos suficientes no podrá visitar esa localización). Tras esto, debe escoger entre:

- Resolver un Encuentro. El jugador procede de la siguiente forma:
    1. Recolectar Bienes. El jugador obtiene 1 bien del tipo de la tienda más 1 bien por cada encantamiento y cada dragón artesano presentes en la tienda de los tipos correspondientes.
    2. Colocar un Dragon Artesano (opcional). Si la tienda tiene al menos un espacio libre para dragones artesanos y el jugador tiene un dragón artesano del tipo correspondiente, puede jugarlo ahora y recibir la bonificación indicada en el espacio de ciudad. Si este era el último espacio disponible de la tienda, se debe revelar una nueva tienda del mazo y colocarla en un espacio libre de la ciudad.
    3. Activar un Dragon Artesano (opcional). El jugador puede activar el efecto de uno de los dragones artesanos presentes en la tienda.
    4. Activar el Efecto de la Tienda (opcional). El jugador puede activar el efecto de la tienda (si lo tuviese).
- Encantar. El jugador procede de la siguiente forma:
    1. Se escoge uno de los encantamientos disponibles en el tablero principal que coincida con el tipo de la tienda visitada, devolviendo a la reserva todos los recursos requeridos.
    2. El jugador recibe las bonificaciones correspondientes. Se pueden utilizar monedas como comodín (salvo que el encantamiento diga lo contrario). Si se usan varias monedas, cada una debe ser de un tipo distinto de bien.
    3. Tras esto, el jugador solapa la carta de encantamiento bajo la tienda y puede activar los efectos que desee de los dragones artesanos presentes en la tienda en el orden que considere oportuno.

Finalmente, se reponen los suministros (de dragones artesanos y/o de encantamientos, revelando nuevas cartas). El jugador debe evaluar si no sobrepasa el límite de 7 unidades de cada tipo de recurso o de 6 cartas de dragón artesano en la mano, devolviendo el exceso.

Tras esto, el turno pasa al jugador de la izquierda.

En cada turno, el jugador activo puede resolver cualquier cantidad de dragones selectos de resolución durante la partida (con símbolo de sol), dejándolos bocarriba en su zona de juego.


# Fin de la partida

El final de la partida se detona en el turno en el que se agota el mazo de encantamientos o de dragones artesanos. Todos los jugadores disfrutarán de un último turno, incluyendo el jugador en cuyo turno se detonó el final de la partida (será el último en jugar).

Una vez todos los jugadores han resuelto su turno final, se procede al recuento final, en el que cada jugador anota:

- 1 Punto de Victoria por cada moneda en su reserva personal.
- Los Puntos de Victoria indicados en los dragones selectos de puntuación de final de partida.

El jugador con más puntos de victoria será el vencedor. En caso de empate, se comprueban los siguientes criterios:

- El jugador con más dragones artesanos en mano
- El jugador con más bienes en su reserva personal.

Si la igualdad se mantiene, los jugadores comparten la victoria.
