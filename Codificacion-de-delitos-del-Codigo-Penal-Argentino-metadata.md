Codificación de delitos del Código Penal Argentino
==================================================

El Código Penal de la Nación (CPN) establece cuáles son los delitos que conforman el sistema penal del país. Sucesivas reformas han extendido su impacto en la vida de los ciudadanos, con el desafío de ponderar el cambiante escenario en que desarrollan su vida en sociedad. La reciente inclusión del delito de Femicidio o bien la definición de “abuso sexual” y las penas contempladas para el mismo dan cuenta de eso.

Luego del trabajo conjunto con las instituciones de justicia de todo el país firmantes del [Convenio Interjurisdiccional de Datos Abiertos de Justicia](https://github.com/datos-justicia-argentina/Convenio-Interjurisdiccional-de-Datos-Judiciales-Abiertos/blob/master/Convenio%20Interjurisdiccional%20de%20Datos%20Abiertos%20de%20Justicia.pdf), se desarrolló la tabla de delitos aquí presentada, con el objeto de mejorar la inter-operatividad en materia de legislación penal.

[http://datos.jus.gob.ar/dataset/codificacion-de-delitos-del-codigo-penal-argentino](http://datos.jus.gob.ar/dataset/codificacion-de-delitos-del-codigo-penal-argentino)

Características
---------------

-   **Fecha de Primera** **Publicación:** 23/02/2018

-   **Tags o Etiquetas:** abusos sexuales, amenazas, cárceles, código penal, daños, delitos, homicidios, hurtos, legislaciones, leyes especiales, presos, robos

-   **Organización:** Ministerio de Justicia y Derechos Humanos. Secretaría de Justicia. Subsecretaría de Política Criminal. Programa de Justicia Abierta

-   **Autor:** Ministerio de Justicia y Derechos Humanos. Secretaría de Justicia. Subsecretaría de Política Criminal. Programa de Justicia Abierta

-   **Responsable:** Ministerio de Justicia y Derechos Humanos. Secretaría de Justicia. Subsecretaría de Política Criminal. Programa de Justicia Abierta

-   **Grupos:** Información Jurídica, Política Criminal

-   **Frecuencia de Actualización:** Eventual

Recursos Disponibles
--------------------

### Codificación de delitos del Código Penal Argentino AAAAMMDD

-   **Nombre del archivo:** codificación-delitos-codigo-penal-argentino-AAAAMMDD.csv

-   **Descripción del contenido:** se detalla cada uno de los delitos enunciados en el Código Penal de la Nación y algunas leyes especiales, con la descripción de los mismos y con un código respectivo. Incluye datos de vigencia de la norma.

-   **Formato:** CSV delimitado por comas, codificado en UTF-8

-   **Rango temporal:** listado actualizado a la fecha AAAAMMDD

### Campos del recurso

-   **orden (int):** ordenamiento que permite una visualización del Código Penal

-   **titulo_completo (string):** número de título, descripción del título y número de capítulo en el que se encuentra el delito mencionado. Para las leyes especiales corresponde el número de ley.

-   **articulo_delito (string):** artículo, párrafo, inciso y parte en la que está mencionado el delito

-   **descripcion_delito (string):** descripción del delito

-   **tipo_delito (string):** tipo de delito. Esta clasificación da cuenta del tipo de correlación que se establece entre cada elemento de la tabla con el Código Penal. Toma los valores:

    -   Específico: refiere a aquellos delitos descriptos con el mayor grado de detalle posible en relación con el artículo, el párrafo, el inciso y la parte, en los casos que corresponda. Ejemplo *“Art. 189 bis Inc. 1 Parte 1 - Tenencia de armas y explosivos de destrucción masiva”*

    -   General: refiere a aquellos delitos descriptos con menor grado de detalle. A todos los artículos le corresponde un valor general que agrupa a todos los incisos y partes que le corresponden. Por ejemplo *“Art. 97 - Duelo regular”*. No contienen valor *general* los artículos correspondientes a los delitos de homicidio, abuso sexual, amenaza, daño, robo y hurto

    -   Específico/General: refiere a aquellos casos en que por artículo se corresponde un solo delito. Ejemplo *“Art. 83 - Instigación o ayuda al suicidio”*

-   **codigo_delito (string):** código único para la identificación específica del delito mencionado

-   **vigente (string):** indica si la norma se encuentra vigente a la fecha de publicación del recurso. Toma los valores SI/NO. Implementado desde la publicación del 11/10/2019.

-   **vigencia_desde (date):** indica la fecha desde la cual la norma está vigente. Se toman en cuenta las normas incluidas, modificadas, actualizadas, etc. a partir del 23/08/2018. Implementado desde la publicación del 11/10/2019.

-   **vigencia_hasta (date):** indica la fecha hasta la cual la norma está vigente, en aquellos casos en que el campo "vigente" es *No*. Se toman en cuenta las normas que perdieron vigencia a partir de 22/08/2018. Implementado desde la publicación del 11/10/2019.


### Codificación de delitos del Código Penal Argentino

-   **Nombre del archivo:** codificación-delitos-codigo-penal-argentino.zip

-   **Descripción del contenido:** contiene todas las tablas de delitos publicadas en el portal. En cada tabla se detallan los delitos enunciados en el Código Penal de la Nación y algunas leyes especiales, con la descripción de los mismos y con un código respectivo. 

-   **Formato:** CSV delimitado por comas, codificado en UTF-8


### Notas

[Ley 27.275 - Derecho de Acceso a la Información Pública]( http://servicios.infoleg.gob.ar/infolegInternet/anexos/265000-269999/265949/norma.htm)

Esta tabla de delitos permitirá organizar y uniformar el análisis y la comprensión de los casos judiciales por parte de las instituciones de justicia y de la ciudadanía en general, en cumplimiento con los estándares de Gobierno Abierto fijados en el Plan de Apertura de Datos del Poder Ejecutivo Nacional consagrado por el [Decreto 117/2016](http://servicios.infoleg.gob.ar/infolegInternet/anexos/255000-259999/257755/norma.htm).

A su vez será de gran utilidad en miras a dar cumplimiento con  el Plan de Implementación que tiene por objeto la adaptación de la clasificación del SISTEMA NACIONAL DE INFORMACIÓN CRIMINAL (SNIC), del SISTEMA NACIONAL DE ESTADÍSTICAS SOBRE EJECUCIÓN DE LA PENA (SNEEP) y del SISTEMA NACIONAL DE ESTADÍSTICAS JUDICIALES (SNEJ) a la Clasificación Internacional de Delitos con Fines Estadísticos elaborado por la Oficina de las Naciones Unidas contra la Droga y el Delito (UNODC), dispuesto por la resolución conjunta del Señor Ministro de Justicia y Derechos Humanos y la Señora Ministra de Seguridad [Resolución Conjunta 1-E/2018](http://servicios.infoleg.gob.ar/infolegInternet/verNorma.do?id=306271).
 
[Código Penal de la Nación Argentina Ley 11.179](http://servicios.infoleg.gob.ar/infolegInternet/anexos/15000-19999/16546/texact.htm)

Leyes especiales:

[Ley 23.737](http://servicios.infoleg.gob.ar/infolegInternet/anexos/0-4999/138/norma.htm)

[Ley 23.184](http://servicios.infoleg.gob.ar/infolegInternet/anexos/25000-29999/26207/norma.htm)

[Ley 25.761](http://servicios.infoleg.gob.ar/infolegInternet/anexos/85000-89999/87496/norma.htm)

[Ley 22.421](http://servicios.infoleg.gob.ar/infolegInternet/anexos/35000-39999/38116/norma.htm)

[Ley 11.723](http://servicios.infoleg.gob.ar/infolegInternet/anexos/40000-44999/42755/norma.htm)
