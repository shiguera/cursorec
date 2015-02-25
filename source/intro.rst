.. intro.rst

Introducción
============

Instalación de Octave 3.8
-------------------------

Durante este curso utilizaremos Octave versión 3.8, la última disponible a la fecha de redactar este manual. Es posible que tengas ya instalada otra versión de Octave o quizás Octave-UPM. Cualquiera de esas aplicaciones te puede servir para seguir el curso, pero te recomendamos la instalación de Octave versión 3.8, que trae importantes mejoras respecto de versiones anteriores de Octave. 

Respecto a los usuarios de Matlab que decidan seguir el curso con Matlab, no deberían encontrar problemas. Si surgiera algún tipo de incompatibilidad entre los ejercicios del curso y Matlab os agradeceremos que nos lo indiquéis, a través del foro, para ir completando una lista de incompatibilidades, que no será grande, y se tratará más bien de pequeños detalles.

En poco tiempo, seguramente antes de acabar este curso, aparecerá la versión 4.0 de Octave, que traerá todavía más mejoras y correcciones de bugs respecto de versiones anteriores. Os tendremos puntuálmente informados a través del foro de novedades de la asignatura.

Para instalar la versión 3.8 de Octave hay que seguir las instrucciones que se dan a continuación, dependiendo del sistema operativo que tengáis instalado en vuestro ordenador.

Los que tengan ordenadores **Mac** con sistema operativo **OSX** pueden seguir las instrucciones que se dan en el `wiki de Octave <http://wiki.octave.org/Octave_for_MacOS_X>`_ [1].

Los usuarios de Linux pueden acceder a la página de descagas del `portal web de Octave <http://www.gnu.org/software/octave/download.html>`_ [2] y seguir las instrucciones que se dan allí.

Los usuarios de sistemas operativos **Windows** tienen que utilizar la versión del instalador que se ofrece en la página `http://mxeoctave.osuv.de [3] <http://mxeoctave.osuv.de>`_ para acceder a todas las características de la versión 3.8. Hay que descargar el instalador y ejecutarlo en nuestro ordenador. También ofrecen una versión portable de *Octave*. Portable se refiere a que no requiere instalación. Se puede copiar en una memoria USB, por ejemplo, y ejecutar en cualquier ordenador con sistema operativo Windows.

[1] http://wiki.octave.org/Octave_for_MacOS_X 

[2] http://www.gnu.org/software/octave/download.html

[3] http://mxeoctave.osuv.de/

Primeros pasos tras la instalación
----------------------------------
Si la instalación ha transcurrido normalmente, al final de la misma deberíamos tener unos accesos directos en el escritorio para poder arrancar Octave en modo consola o en modo gráfico. Si arrancamos Octave en modo gráfico accederemos al Graphic User Interface de Octave. En la siguiente figura se muestran las diferentes secciones de la ventana gráfica de Octave.

.. image:: octavegui.png
   :width: 800px
   :alt: octavegui


.. Note:: Si no se tienen accesos directos al programa tras la instalación se puede intentar lo siguiente:

	- **Localizar el directorio ***bin*** de la instalación:** Lo primero que tenemos que hacer es localizar el directorio donde ha quedado instalado el programa. Durante la instalación se nos ofrece instalar en algo parecido a **C:\\Octave\\Octave-3.8.1**. En general será algo parecido a *C:\\Programs\\Octave* o *C:\\Octave* o también *C:\\Archivos de Programa\\Octave*. En cualquier caso, dentro del directorio de la instalación debemos localizar el directorio **bin**, que es donde se encuentran los programas ejecutables de *Octave*. 

	- **Añadir la ruta del directorio bin a la variable path del sistema:** La variable *path* del sistema guarda una lista de directorios separados por *';'*. Estos directorios es donde el sistema operativo busca cada vez que tiene que ejecutar un programa. En el siguiente enlace: `Cómo cambiar el path de Windows <http://blogs.itpro.es/jioller/2011/03/25/cambio-del-path-de-windows/>`_ explican como hacer el cambio. El cambio que hay que hacer es añadir al final de la cadena *path* existente un *';'* y la ruta del directorio *bin* que será algo parecido a *C:\\Octave\\bin*. (ver Nota 1)

	- **Poner en el escritorio accesos directos a *Octave*:** Tenemos que prestar atención a los archivos **octave.exe** y **octave-gui.exe**. Son los programas que arrancan *Octave* en modo consola y en modo gráfico, respectivamente. (*GUI es el acrónimo de Graphic User Interface*). Podemos crear unos accesos directos a ambos programas y tenerlos disponibles en el escritorio, de forma que podamos acceder rapidamente a *Octave*. Para aprender cómo crear accesos directos en Windows podéis consultar el siguiente enlace. **TODO**







