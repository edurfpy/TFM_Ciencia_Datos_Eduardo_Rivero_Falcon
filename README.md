# TFM_Ciencia_Datos_Eduardo_Rivero_Falcon
Repositorio con el código del TFM del Máster oficial en Ciencia de datos por la UOC

TEMA TFM: ANÁLISIS Y VISUALIZACIÓN DE LOS FACTORES DETERMINANTES DEL ESTADO DE SALUD EN LA UNIÓN EUROPEA
Autor: Eduardo Rivero Falcón
Directora: Susana Pérez Álvarez
Fecha: Enero 2021

Este repositorio contiene el código y archivos necesarios de este Trabajo Fin de Máster, dividido en 3 carpetas:


1.- CARPETA "PYTHON":
  
  Código correspondiente de la etapa de PREPROCESADO implementado en el lenguaje Python. Consta de 4 'Jupyter Notebooks':
    * 'automatiz_prx_indep_EHIS.ipynb'
    * 'procesado_otros.ipynb'
    * 'procesado_variables_datos_faltantes.ipynb'
    * 'crear_dataset_final.ipynb'
    
   También están disponibles las salidas correspondientes en 'html' por si se quiere consultar sin ejecutar.
   
   Se encuentra finalmente la carpeta 'data' con los datos necesarios y los producidos por la ejecución del código. Contiene las siguientes        subcarpetas:
      * 'origen': carpeta con los archivos 'csv' descargados de la página web de datos abiertos del Eurostat, uno por cada variable.
      * 'procesado': carpeta con los archivos fruto del preprocesado de los archivos de la carpeta 'origen' (3 primeros notebooks)
      * 'FINAL': carpeta que contiene el archivo que une en un único dataset los datos del archivo de preprocesado, y el mismo con dos últimas correcciones, versión final ('health_determ_EU_v0.csv', creado en el último notebook)
      
      
2.- CARPETA "R":

  Código correspondiente de la etapa de ANÁLISIS implementado en el lenguaje R, en el archivo de RMarkdown 'tfm_final.Rmd'. También está disponible su salida en 'html' por si se quiere consultar sin ejecutar.
  
  Finalmente tenemos la carpeta 'data', con el archivo de entrada producto final del preprocesado mencionado anteriormente 'health_determ_EU_v0.csv' y 2 archivos 'csv' producidos con los datos necesarios para la visualización en TABLEAU: 'Hlth_Determ_EU_Vis_Tableau.csv' y 'analisis_PCA_Vis_Tableau.csv'.
  
  
  3.- CARPETA "TABLEAU":
  
    Contiene el archivo creado en el programa de visualización TABLEAU.
