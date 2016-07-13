Fomentando La Cultura
===========

Descripción General
-------------------

El proyecto a desarrollar es la creacion de una aplicacion web que ayude a 
promover la cultura en Quetzaltenango. La aplicacion tendra una agenda sobre 
eventos de cultura, estos podran ser filtrados a gusto del usuario-visitante.
Los eventos tendran informacion detallada sobre lugar, día, precio, etc. 

Aparte de la agenda, existira un directorio de artistas con un perfil, 
el cual tendra su datos personales. La validacion del registro de los 
artistas estara a cargo del administrador, él cual verificara datos correctos 
con respecto del mismo. La creacion de los eventos seran los artistas y
el administrador. Al igual que el registro de artistas, se validaran los 
eventos creados por los artistas. La agenda estara categorizada, para una mejor 
busqueda.

-------
Modulos
-------

Usuarios
^^^^^^^^

Modulo donde se registraran, crearan su perfil y actualizaran datos.
Divido en tres submodulos:

Usuario comun:

En este modulo se manejaran las acciones que puede hacer el usuario como
escribir reseña a artista o evento, seguirlos, etc.

Artista:

Modulo donde tiene las caracteristicas del usuario comun, agregando que el 
artista podra crear eventos y asignar artista al evento.

####Administrador:

Modulo donde el usuario tiene todos los privilegio donde podra hacer la gestion
de usuarios comunes, artistas y eventos. La creacion de capsulas informaticos y 
la verificacion de estadististicas.


Gestion de Eventos
^^^^^^^^^^^^^^^^^^

Modulo que contemplara el control de la creacion de eventos.Por parte del 
administrador validara los eventos creados por el artista, asimismo, creara 
sus propios eventos.  

Gestion de Usuarios
^^^^^^^^^^^^^^^^^^^^

Modulo donde se tendra el control del registro y los privilegios de un artista y 
de un usuario-visitante a cargo del administrador. Asi como la validacion y 
verificacion del registro.  

Capsulas Informativas
^^^^^^^^^^^^^^^^^^^^^^

Modulo donde el administrador podra enviar informacion cultural sobre fechas 
conmemorativa o importantes que tengan que ser del conocimiento del usuario 
comun.

Estadisticas
^^^^^^^^^^^^

Modulo donde se tendran el control de los datos que se vayan generando por las 
acciones que hagan los usuarios comunes y artistas con la finalidad de estas 
estadisticas nos ayuden a la toma de decisiones posteriormente.

Directorio
^^^^^^^^^^

EL modulo tendra todos los artistas creados, gestionara una busqueda categorizada
para una mayor eficiencia por tipo de artista, nombre, entre otros. Aparte el artista 
tendra informacion detallada de el y como contactarlos. Tendra un diseño de forma de 
cartelera.
