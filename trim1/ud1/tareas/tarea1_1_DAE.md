#1 INTRODUCCIÓN A LAS BASES DE DATOS
**Nombre del alumno**: *vaitiare Rodriguez Farrais. Clase DAW, grupo B.*
 Para realizar esta práctica nos serviremos de Internet y buscaremos respuestas a estas preguntas donde la misma tenga que ver con todo lo explicado anteriormente.
![base de datos](https://i.ytimg.com/vi/jl_plER1SLU/maxresdefault.jpg)
1. ¿Qué es un archivo o fichero?
**En informática, se conoce como archivo o fichero a un conjunto organizado de unidades de información (bits) almacenados en un dispositivo. Se les denomina de esa manera como metáfora a partir de los archivos tradicionales de oficina, escritos en papel, ya que vendrían a ser su equivalente digital**
2. Tipos de ficheros.
*Podemos dividir los archivos en dos grandes grupos. Éstos son los ejecutables y los no ejecutables o archivos de datos. La diferencia fundamental entre ellos es que los primeros están creados para funcionar por si mismos y los segundos almacenan información que tendrá que ser utilizada con ayuda de algún programa.*
Los tipos de archivo más comunes son:
- De texto: txt, doc, docx, etc.
- De imagen: jpg, gif, bmp, png, etc.
- De vídeo: avi, mp4, mpeg, mwv, etc.
- De ejecución o del sistema: exe, bat, dll, sys, etc.
- De audio: mp3, wav, wma, etc.
- De archivo comprimido: zip, rar, tar, etc.
- De lectura: pdf, epub, azw, ibook, etc.
- De imagen de disco: iso, mds, img, etc.
3. Define brevemente los conceptos de registro y campo.
**Campo** (informática) es un espacio de almacenamiento para un dato en particular.
En las bases de datos, un campo es la mínima unidad de información a la que se puede acceder; un campo o un conjunto de ellos forman un registro, donde pueden existir campos en blanco, siendo este un error del sistema operativo. Aquel campo que posee un dato único para una repetición de entidad, puede servir para la búsqueda de una entidad en específico.
**Registro** (base de datos) también llamado fila o tupla, representa un objeto único de dato estructurados en una tabla. En términos simples, una tabla de una base de datos puede imaginarse formada de filas y columnas o campos. Cada fila de una tabla representa un conjunto de datos relacionados, y todas las filas de la misma tabla tienen la misma estructura.
Un registro es un conjunto de campos que contienen los datos que pertenecen a una misma repetición de entidad. Se le asigna automáticamente un número consecutivo (número de registro) que en ocasiones es usado como índice aunque lo normal y práctico es asignarle a cada registro un campo clave para su búsqueda.
4. ¿Qué es una base de datos?
Una base de datos es una colección de información organizada de forma que un programa de ordenador pueda seleccionar rápidamente los fragmentos de datos que necesite. Una base de datos es un sistema de archivos electrónico.
Las bases de datos tradicionales se organizan por campos, registros y archivos.
5. Diferencias entre un sistema convencional de archivos y un Sistema Gestor de Base de Datos.
La diferencia clave entre el sistema de archivos y la base de datos es que el sistema de archivos administra solo el acceso físico, mientras que la base de datos administra el acceso físico y lógico a los datos.
La base de datos y el sistema de archivos son dos métodos que ayudan a almacenar, recuperar, administrar y manipular datos. Ambos sistemas permiten al usuario trabajar con datos de manera similar. Un sistema de archivos es una colección de archivos de datos sin procesar almacenados en el disco duro, mientras que una base de datos está diseñada para organizar, almacenar y recuperar fácilmente grandes cantidades de datos. En otras palabras, una base de datos contiene un conjunto de datos organizados en forma digital para uno o más usuarios.
6. Componentes de un Sistema Gestor de Base de Datos.
Un sistema de gestión de base de datos consta de varios componentes, todos los cuales contribuyen al buen funcionamiento del software. Los elementos básicos que lo conforman son tres: el diccionario de datos, el lenguaje de definición de datos y el lenguaje de manipulación de datos.
- **Diccionario de datos**: consiste en una lista de metadatos que reflejan las características de los diversos tipos de datos incluidos en la base de datos. Además, estos metadatos informan sobre los permisos de uso de cada registro y su representación física. De esta manera, el diccionario proporciona toda la información relevante sobre los datos almacenados.
- **Lenguaje de definición de datos**: el lenguaje de definición de datos, también llamado lenguaje de base de datos o DDL (data definition language), sirve para estructurar el contenido de la base de datos. Gracias a este lenguaje, es posible crear, modificar y eliminar objetos individuales, como referencias, relaciones o derechos de usuario.
- **Lenguaje de manipulación de datos**: mediante el lenguaje de manipulación de datos o DML (data manipulation language), se pueden introducir nuevos registros en la base de datos, así como eliminar, modificar y consultar los que ya contiene. Este lenguaje también permite comprimir y extraer los datos.
7. Tipos de usuarios de las bases de datos, funciones y características de cada uno de ellos.
**Usuarios normales**: Son usuarios no sofisticados que interactúan con el sistema mediante un programa de aplicación con una interfaz de formularios, donde puede rellenar los campos apropiados del formulario. Estos usarios pueden también simplemente leer informes generados de la base de datos.

**Programadores de aplicaciones**: Son profesionales informáticos que escriben los programas de aplicación, utilizando herramientas para desarrollar interfaces de usuario, como las herramientas de desarrollo rápido de aplicaciones (DRA), que facilitan crear los formularios e informes sin escribir directamente el programa.

**Usuarios sofisticados**: Interactúan con el sistema sin programas escritos, usando el lenguaje  de consulta  de base de datos para hacer sus consultas. Los analistas que envían las consultas para explorar los datos en la base de datos entran en esta categoría, usando ellos las herramientas de procesamiento analítico en línea (OLAP, OnLine Analytical Processing), o herramientas de recopilación de datos.

**Usuarios especializados**: Son usuarios sofisticados que escriben aplicaciones de bases de datos especializadas y adecuadas para el procesamiento de datos tradicional. Entre estas aplicaciones están los sistemas de diseño asistido por computadora, sistemas de base de conocimientos y sistemas expertos,  sistemas que almacenan datos de tipos de datos complejos (como gráficos y de audio) y sistemas de modelado de entorno.

**Administradores de la base de datos (ABD)** Son las personas que tienen el control central del SGBD. Entre las funciones del ABD se encuentran:
- Definición del esquema de la base de datos.
- Definición de la estructura y el método de acceso.
- Modificación del esquema y la organización física.
- Concensión de autorización para el acceso a los datos.
- Mantenimiento rutinario.
8. Organización de una base de datos.
Una organización de datos es una estructura física-lógica
que permite realizar operaciones computacionales
(editar, guardar, actualizar, etc.) sobre un contenido de
información.
- Estructura física; describe la manera física (bytes) de
almacenar los datos en un soporte (como se almacenan los
datos en el soporte).
- Estructura lógica; describe la manera lógica de representar
la información a los usuarios (como ve el usuario la
información).
9. Modelos de bases de datos.
![modelos](http://1.bp.blogspot.com/-vle6qeLCVu4/VYo-sqaM6QI/AAAAAAAAADE/TjaU5UV25q0/s1600/modelos-de-bases-de-datos.png)
10. Tipos de archivos según su función en el tiempo
Los elementos de un archivo pueden ser de cualquier tipo, simples o estructurados o según su función.
**SEGÚN SU FUNCIÓN.**
- Archivos Permanentes: Son aquellos cuyos registros sufren pocas o ninguna variación a lo largo del tiempo, se dividen en:
Constantes: Están formados por registros que contienen campos fijos y campos de baja frecuencia de variación en el tiempo.
De Situación: Son los que en cada momento contienen información actualizada.
Históricos: Contienen información acumulada a lo largo del tiempo de archivos que han sufridos procesos de actualización o bien acumulan datos de variación periódica en el tiempo.
- Archivos de Movimiento
Son aquellos que se utilizan conjuntamente con los maestros (constantes), y contienen algunos campos comunes en sus registros con aquellos, para el procesamiento de las modificaciones
- Archivo de Maniobra o Transitorio
Son los archivos creados auxiliares creados durante la ejecución del programa y borrados habitualmente al terminar el mismo.
