# Factions - Guía completa

## Acerca de Factions
Las facciones (alias factions en ingles) son grupos de usuarios unidos que pelean contra otros. Cada faction puede adquirir terrenos del mundo PVP para realizar ahí sus construcciones en grupo.

Cualquier usuario puede unirse a otra faction pero para eso debe ser aceptado por algún miembro superior de la faction.

Pueden ver la información de una Faction con el comando `/f f <faction>`.

Cuantos más habitantes tiene una Faction más terrenos podrá comprar (El Mundo PVP es un mundo de guerras donde cada faction puede claimear donde desee y no hay problema por claimear al lado o alrededor de otra faction como lo es en Towny).

Dentro de cada Faction, cada terreno que se anexe a la misma puede ser utilizado por todos los habitantes de la Faction  (para invitar habitantes ver el comando abajo), pero el staff de la Faction podrá decidir que algunas parcelas sean privadas.

## Como crear una Faction

Para formar una faction ya no se necesita dinero. Primero necesitan ver donde será el terreno de la Faction (que sea un lugar abierto y grande que permita la expansion luego y que no perjudique otras cosas), una vez que tengan el lugar sigan lo siguiente (siempre sin los [ ] ):

`/f create [nombre de la Faction]`

Luego ponemos: 

`/f desc [descripcion de la faction]`

Bien ahora necesitamos agregar dinero a nuestra Faction ya que todas las compras de terreno que hagamos se descontaran del banco de la Faction, y para esto hacemos asi:

`/f money deposit [cantidad]`  
└ Ejemplo: `/f money deposit Cameron 5000`

Una vez hecho esto deberán marcar un terreno para la Faction (ya que hasta ahora solo creamos el nombre y agregamos dinero al banco de la Faction). Para marcar el primer terreno (de 16 x 16) una vez que tengamos decidido el lugar y estemos en el, escribimos:

`/f claim`

Ahora hemos marcado el primer terreno, luego podemos ir comprando más terrenos de 16 x 16 con  `/f claim` al lado de los terrenos que tengamos marcado (o sea si yo compre el terreno inicial de 16 x 16 en un lado no puedo comprar en ningun otro lado que no este pegado al que compre primero o a los que he comprado).

Hemos logrado crear una Faction! Ve abajo la lista de comandos abajo para más información.

## Comandos

Cuando el comando tiene:
- `< >` significa que el argumento **es obligatorio**, la información debe ser especificada.
- `[ ]` significa que el argumento **es opcional**, no es necesario especificarlo.

### Comandos Básicos 

`/f help [numero de pagina]` – Muestra la ayuda del plugin incluyendo todos los comandos mencionados en este post.  
`/f list [numero de pagina]` – Muestra la lista de Factions.  
`/f show <nombre de la faction>` – Muestra información de la Faction especificada.  
`/f map` – Te muestra un mapa de las factions cercanas por el chat (Puede resultar muy confuso).  
`/f power` – Muestra tu poder.  
`/f player [usuario]` – Muestra tu información de factions o la de otro jugador si especificas un nombre.  
`/f faction [faction]` – Muestra información sobre tu faction o la información de otra si especificas el nombre.  
`/f join <faction name>` – Para unirte a la faction especificada (siempre y cuando: te hallan invitado o porque la faction sea abierta para que cualquiera se pueda unir).  
`/f leave` – Para abandonar la Faction.  
`/f home` – Te lleva al home de la Faction.  
`/f map` – Muestra un mapa de los chunks y a que faction pertenecen.  

### Comandos para crear/editar una faction
`/f create <faction tag>` – Para crear una Faction (necesitas tener suficiente dinero).  
`/f desc <desc>` – Para cambiar la descripción de tu Faction (es recomendable ponerle una descripción apenas la hallas creado, de todas formas la podrás modificar más adelante).  
`/f sethome` – Para setear un lugar como home de la Faction.  
`/f name <faction tag>` – Cambiar el nombre de tu Faction (Cada cambio cuesta dinero).  

### Administración de miembros
`/f open` – Para cambiar si se necesita una invitación para entrar a la Faction o puede entrar cualquiera, por defecto viene establecido que se necesite invitación).  
`/f invite <nombre del jugador> [yes|no]` – Invitar a un jugador a que se una a la Faction, se puede especificar "no" o "yes" al final del comando para cancelar o activar la invitación.  
`/f kick <nombre del jugador>` – Kickea un jugador de la Faction (solo en caso extremo cuando al miembro se le pide que abandone por una causa razonable pero el se niega a irse) Este comando solo lo pueden utilizar los moderadores y admins de la faction.  
`/f title <nombre del jugador> <title>` – Le da un "Titulo" al jugador, las demás personas cuando vean la información de la faction esa persona tendrá ese "titulo" delante del nombre.  
`/f promote <usuario>` – Para ascender de rango a un miembro de la faction.  
`/f demote <usuario>` – Para bajarle el rango a un miembro de la faction.  
`/f officer <usuario>` – Para darle rango de oficial a un miembro de la faction (alias el Moderador) (Pueden haber varios oficiales).  
`/f leader <usuario>` – Para setear el nuevo líder de la faction (alias Dueño) (Solo puede haber 1 líder).

### Dinero
`/f money` – Para ver la ayuda de todos los comandos de dinero.  
`/f money balance [faction]` – Para ver el dinero de tu faction o de otras.  
`/f money deposit <cantidad>` – Para depositar dinero de tu cuenta al banco de la faction.  

### Administración de terrenos
`/f seechunk` – Para ver el chunk en el que te encuentras parado. (En vez de seechunk se puede usar sc).  
`/f claim` – Agregar terreno de 16 x 16 a la Faction (Incluye desde la bedrock hasta el cielo).  
`/f unclaim` – Para sacar el terreno de 16 x 16 en el cual estes parado de tu Faction (ten en cuenta que solo se te devolverá una pequeña parte de lo que gastaste para comprarlo).  
`/f access` – Para ver ayuda sobre los comandos de acceso.  
`/f access <usuario>` –  [A definir...]  
`/f owner <nombre del jugador>` – Establece/saca el dueño del terreno en que este parado de 16 x 16.  
`/f ownerlist` – Para ver la lista de dueños del terreno en el que te encuentras.

`/f mod <nombre del jugador>` – Le da el rango de Moderador a uno de los miembros de tu Faction.  
`/f admin <nombre del jugador>` – Le das tu rango de Admin de la Faction a otro jugador y pasas a ser Moderador (solo puede haber un admin al mismo tiempo, en otras palabras con este comando ya no serias más dueño de la faction seria la persona que especificaste.

`/f noboom` – Activa/desactiva las explosiones dentro de la Faction (solo si la Faction es pacifica, más información abajo).

### Comandos de Diplomacia
`/f ally <faction name>` - Para hacer la faction especificada aliada de tu faction.  
`/f neutral <faction name>` - Para hacer la faction especificada neutral a tu faction.  
`/f enemy <faction name>` - Para hacer la faction especificada enemiga de tu faction.  
`/f money balance` - Para mostrar el dinero de la Faction en la cual eres miembro, staff o dueño.  
`/f money ff <amount> <faction> <faction>` - Transferir dinero de tu Faction a otra Faction (es usado generalmente entre factions aliadas, para ayudarse mutuamente).


## La guerra y el poder

Las factions en el servidor tienen relaciones entre sí. Pueden ser aliado, neutral o enemigo. Puedes elegir la relación con otra facción a través de los comandos de chat nombrados anteriormente  

Para que dos Factions sean aliadas ambas deben desearlo (técnicamente las dos tiene que escribir el comando de alianza).
Para que dos Factions sean enemigas ambas deben desearlo (ya que sino seria injusto que una Faction grande le declare guerra a las pequeñas que no puedan defenderse).
No podrás atacar a miembros de tu Faction ni de las Factions aliadas a la tuya.
No podrás hacerle daño a miembros de Factions neutrales a la tuya en su terreno aunque SI podrás afuera de su territorio.
Si podrás hacer daño a los miembros de Factions enemigas a la tuya.
  
Sólo los miembros de facciones pueden construir y destruir en su propio territorio. Interacción con los siguientes elementos también se restringe por defecto: puerta de madera, trampilla, Horno, Calentador, etc. Asegurate de poner las placas de presión frente a las puertas si quieres que visitantes/invitados entren. También se puede usar esto para crear áreas de miembros solamente. Como dispensadores están protegidos se puede crear trampas sin preocuparse de que las flechas sean robadas.
  
Cada jugador tiene "poder". El poder va desde 0 a 10. Si mueres pierdes energía. Tenga en cuenta que no importa en absoluto cómo se muere. Puede ser asesinado por un enemigo o se ahogan en el agua. En cualquier caso perderás 1.0 de poder. El poder se regenera mientras el jugador está online, mientras que offline su poder no se regenera. Se tarda 5 minutos para un poder para ser restaurada, mientras que en línea.

## Aclaraciones

- La palabra claimear se refiere al hecho de hacer un _claim_ (reclamar) un terreno.
- Puede pasar que no te deje expandir tu faction y esto puede ser porque:
    1. El nivel de tu poder es muy bajo (trata de no morir tantas veces).
    2. Te falta miembros en tu Faction para que te permita la expansión.
    3. Te olvidaste de agregar el dinero al banco de la faction.
- Las factions solo se pueden claimear en el mundo PVP.