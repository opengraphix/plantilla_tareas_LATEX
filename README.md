# Plantilla para tareas en LATEX

Archivos para elaborar tareas o trabajo sencillos utilizando LATEX, se puede emplear para sistemas MS Windows, GNU/Linux y OSX.

Se debe emplear la siguiente estructura para la entrega de trajos:

- PaternoMatenoN_plantillatarea


Elemento | Descripción |
--- | --- |
Paterno | Apellido paterno iniciando con la primera letra en mayúscula. |
Materno | Corresponde al apellido materno iniciando con la primera letra en mayúscula. |
N | Inicial del primer nombre, sí se tiene dos nombre utilizar las iniciales de cada uno en mayúsculas.
_ | Guión bajo se emplea como separación. |
plantillatarea | Es el nombre de la tarea o unidad solicitada. | 


Ejemplo:

- Nombre: Luis Octavio Ramírez Fernández
- Tarea: Unidad 1

RamirezFernandezLO_unidadI.tex

## Cómo iniciar
~~~sh
git clone https://github.com/opengraphix/plantilla_tareas_LATEX.git

cd plantilla_tareas_LATEX
~~~

Abrir el archivo PaternoMatenoN_plantillatarea.tex con tu procesador de textos favorito para LaTeX (Atom, Emacs, VIM, Texmate, TexMaker) y guardalo con tus datos.

## Agregar bibliografía
Las nuevas fuentes bibliográficas se agregan en *biblio/bibliografia.bib*

### Actualizar y compilar la biblografía

Desde la línea de comandos ejecutar las siguientes instrucciones, para habilitarla.

~~~sh
latex PaternoMatenoN_plantillatarea
bibtex PaternoMatenoN_plantillatarea
latex PaternoMatenoN_plantillatarea
latex PaternoMatenoN_plantillatarea
~~~
## Requerimientos
### Windows
- MiKTeX, [http://miktex.org](http://miktex.org/download)
- Texmaker, [www.xm1math.net/texmaker/](http://www.xm1math.net/texmaker/download.html)

### OSX
- MacTeX, [https://tug.org/mactex/](https://tug.org/mactex/downloading.html)
- Texmaker, [www.xm1math.net/texmaker/](http://www.xm1math.net/texmaker/download.html)

### Linux
- Latex, instalar según tu distribución con apt-get, yum, zypper, pacman o tgz.
- Texmaker, [www.xm1math.net/texmaker/](http://www.xm1math.net/texmaker/download.html)
