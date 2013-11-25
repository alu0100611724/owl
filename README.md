Práctica 5. Herramienta Doxygen 
===============================

------------------------------
Instalacion Doxygen en Windows
------------------------------
Descargar el fichero "doxygen-1.8.5-setup.exe" de la pagina: 
http://www.stack.nl/~dimitri/doxygen/download.html

Una vez descargamos el fichero lo ejecutamos y en Select Components seleccionamos solo la opcion:
doxywizard GUI 

-----------------------
Integracion con Eclipse
-----------------------
Abrimos Eclipse y seleccionamos en la pestaña Help "Install New Software"
Introducimos la direccion: http://download.gna.org/eclox/update
Seleccionamos Eclox, aceptamos los términos de uso, finalizamos y reiniciamos

-------------------
Comenta el Proyecto
-------------------
En el proyecto que deseamos documentar escribir comentarios de la siguiente forma

/**
 * Comentario
 */

Para mayor informacion acerca de los comentarios visita: 
http://www.stack.nl/~dimitri/doxygen/manual/docblocks.html

-----------------------
Genera la Documentacion
-----------------------
Presionamos la @ azul y se nos abre una pestaña para configurar la creacion del documento doxygen.
Le asignamos nombre y version a la documentacion.
Indicamos la ruta donde se encuentra el proyecto.
Marcamos la casilla de busqueda recursiva.
Dejamos por defecto el directorio de salida.
En el apartado modo seleccionamos "all entities"
Seleccionamos el lengueje java en este caso.
Seleccionamos los formatos de salida: HTML y Latex.
Por ultimo guardamos y hacemos clic en la @.

-----------------------
OWL API main repository
-----------------------
The OWL API is a Java API for creating, manipulating and serialising OWL Ontologies. 
The latest version of the API supports OWL 2.

It is available under Open Source licenses (LGPL and Apache).

The following components are included:

An API for OWL 2 and an efficient in-memory reference implementation
RDF/XML parser and writer
OWL/XML parser and writer
OWL Functional Syntax parser and writer
Turtle parser and writer
KRSS parser
OBO Flat file format parser
Reasoner interfaces for working with reasoners such as FaCT++, HermiT, Pellet, Racer, JFact and Chainsaw.
