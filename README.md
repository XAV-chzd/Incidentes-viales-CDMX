# Análisis de los incidentes viales para la determinación de distribuciones de densidad y comparativa de incidencia con las rutas del sistema de transporte y las principales vías de la CDMX

## Equipo 5

**Integrantes**

-Ximena Ávila Villagómez

-Félix Alberto Nieto García

-Alejandro De Fuentes Martínez

## Resumen 
El proyecto consiste en realizar un análisis estadístico de los datos de incidentes viales en la CDMX desde el 2014 hasta el 2021 para determinar la distribución a lo largo de las diferentes alcaldías, comparar la densidad de incidentes viales  con las rutas del sistema de transporte y las vías principales de la CDMX y determinar si existe una relación espacial.

Los datos de incidentes viales fueron recopilados por El Centro de Comando, Control, Cómputo, Comunicaciones y Contacto Ciudadano  ( [C5](https://www.c5.cdmx.gob.mx/)) de la Ciudad de México, la cual es la dependencia del Gobierno  encargada de captar información para la toma de decisiones en la capital del país a través del video monitoreo, de la captación de llamadas telefónicas y de aplicaciones informáticas de inteligencia. Los datos de las rutas del sistema de transporte y las vias principales  de la ciudad de México fueron proporcionados por La Secretaría de Movilidad ([EMOVI](https://www.semovi.cdmx.gob.mx/)), es la entidad pública del gobierno de la Ciudad de México encargada de fomentar, impulsar, estimular, ordenar y regular el desarrollo de la movilidad en la Ciudad de México, tomando el derecho a la movilidad como referente y fin último en la elaboración de políticas públicas y programas.


## Contenido

1. **Un Jupyter Notebook**: Se presenta el [código]( https://github.com/Felix-07/Accidentes-Viales-CDMX/blob/main/Proyecto/Proyecto_Fase_3.ipynb) en formato *ipynb* en donde se muestra proceso de cada una de las partes del proyecto, así como los resultados obtenidos. 

2. **Vídeo**:Se adjunta el [link del vídeo](https://www.youtube.com/watch?v=wOxBCGTsbOY) donde cada uno de los integrantes expone de manera breve cada parte del proyecto.


3. **Datasets**: Se adjunta los archivos utilizados durante el procesamiento en la [carpeta de google drive](https://drive.google.com/drive/folders/1eOCVO0lTw0F0eGiyR4zmuDStKTfZ0Qqh?usp=sharing).


## Índice de contenido

0. Librerías

    0.1 Instalación de librerías

    0.2 Librerías utilizadas

1. Identificación del problema
2. Plantemiento de preguntas
3. Colección de datos

    3.1 Funciones para la adquisición de datos mediante API y su tranformación

    3.2 Datos de incidentes víales C5

    3.3 Datos de la demarcación territorial de la CDMX

    3.4 Datos de las vías principales de la CDMX 

    3.5 Datos de las Rutas de transporte de la CDMX

    3.6 Visualización de las rutas de transporte, vías pincipales y demarcación territorial

4. Distribución de las coordenadas

    4.1 Estimados de locabilidad y variabilidad de las coordenadas

    4.2 Distribución espacial de los accidentes de la CDMX

    4.3 Selección de los puntos con mayor incidencia

5. Distribución de variables categóricas

    5.1 Distribuciones generales

    5.2 Análisis Multivariable

    5.3 Visualización del análisis multivariable

6. Serie de tiempo

7. Comparación de los datos

    7.1 Rutas y vías vs alta densidad 

8. Cluster

9. Conslusiones

10. Planes a futuro


## Notas
* Debido a la naturaleza de GitHub no es posible mostrar las graficas y mapas interactivos dentro del código. Si se desea ver las graficas y mapas puede ejecutar el [Jupyter notebook versión Colab](https://colab.research.google.com/gist/Felix-07/ef847e8900d2089239aa094014fddbbc/proyecto-fase-3.ipynb ).

* Se puede vizualizar el [mapa](https://felix-07.github.io/Accidentes-Viales-CDMX/Mayor_incidencia_y_ruta_mapa.html) los regiones de alta densidad de incidentes viales en superposición con las rutas y vias principales de transporte publico. 
