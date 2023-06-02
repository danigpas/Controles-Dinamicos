# Controles-Dinamicos
Repositorio sobre Controles Dinamicos 2.0

23/05/2023
En este repositorio vamos a recoger todo el proyecto que trata sobre la gestión de la Base de Datos MySQL gestion_almacen.
Para ello vamos a crear un Windows Forms en C# en el IDE Visual Studio 2022 donde vamos a generar una primera vista con todas las tablas de esa BBDD y el cliente podrá
elegir la tabla que quiera y trabajar con ella siguiendo el estandar CRUD (se podrá seleccionar cualquier tabla, Editar cualquier campo, Borrar cualquier fila y Añadir
tantas filas como se desee.
Además se ha implementado que se pueda buscar dentro de la tabla que tengamos abierta en ese momento.
Lo último que se ha añadido es la creación de componentes en tiempo real, al pulsar una tabla esta se abre y de forma dinámica se crea un TextBox junto con un label por
cada columna que tiene la tabla abierta.

24/05/2023
Hoy se ha añadido la funcionalidad del Botón Nuevo, que borra todo el texto que tuviesen las cajas de texto para poder crear una nueva fila de esa tabla más adelante al 
pulsar el botón grabar


30/05/2023
Ya se han implementado todas estas funciones:
-Busqueda en cualquier tabla que se tenga abierta en la pestaña Datos
-Todos los botones (Nuevo,Grabar y Borrar) funcionando en cualquier tabla que tengamos abierta
-Creación de los componentes de forma dinámica (Incluidos los que se crean en la última pestaña del tabcontrol, que van cambiando segun que tabla tengamos abierta)

Además se ha comentado todo el proyecto para que sea mucho mas fácil identificar que hace cada función para cualquier persona que quiera ver el proyecto.
En resumen se ha creado la versión 3.0 del proyecto de forma exitosa.


02/06/2023
Versión 4.0 -> Ya se ha cambiado el menu inicial que era una tabla a Botones individuales de cada tabla con sus respectivas fotos identificativas y nombre para cada tabla.
Además se ha implementado el cambio de las cabeceras de todas las tablas (a su vez tambien de los labels de la pestaña datos) por su respectivo nombre en la tabla def_campos. Se ha cruzado el proyecto con las dos nuevas tablas de la base de datos def_tablas y def_campos.
Se ha arreglado el método de busqueda para que respete el cambio de las cabeceras y los metodos de edición y navegación tambien se han corregido.
