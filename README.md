# Proyecto 1: Exploracion de Datos
El objetivo de este proyecto es realizar un primer análisis exploratorio sobre un dataset, partiendo de la importación de las bibliotecas necesarias para la exploración y descripción de los datos. Para este análisis se utilizan las bibliotecas Pandas, Numpy, Seaborn y MatplotLib. Se trabaja sobre el dataset en el siguiente orden:

-	Descripción de los atributos que serán analizados.
-	Importación de las bibliotecas necesarias para la exploración.
-	Carga y lectura del dataset, ordenando las instancias por fecha de creación de las mismas.
-	Visualización del dataset y su forma, cantidad de filas y columnas presentes.
-	Se empieza a analizar la variable que brinda información sobre el tipo de propiedad, se agrupan y se cuentan los valores similares.
-	En este caso se quiere realizar un informe sobre categorías correspondientes a vivienda, por ello se filtran y descartan las que no corresponden.
-	Con un nuevo DataFrame creado a partir del filtro anterior, se visualizan gráficamente en un countplot de Seaborn las categorías de vivienda.
-	Verificación de la existencia de valores nulos o faltantes (nan) en las columnas de interés para el análisis. En caso de existencia, se eliminan o reemplazan con otro valor, según convenga.
-	Comprobación de la existencia de datos erróneos que pueden afectar el análisis, dependiendo de la cantidad se decide si se eliminan o se utiliza otra herramienta para corregirlos.
-	Análisis de categorías agrupadas en forma porcentual, por ubicación geográfica.
-	Visualización gráfica de la distribución porcentual anterior con subplots de MatplotLib.
-	Descripción de medidas estadísticas sobre el atributo precio por metro cuadrado.
-	Cálculo de cuartiles y percentiles para observar si hay presencia de valores extremos, que estén muy alejados de la distribución.
-	Ante la presencia de estos valores extremos, se descartan las instancias cuyos valores de precio por metro cuadrado se encuentren por fuera de los percentiles 10 y 90.
-	Visualización gráfica del precio por metro cuadrado por barrio con un barplot de Seaborn.
-	Se muestran cuáles son los barrios más caros y cuales los más baratos.
-	Comparación gráfica de la distribución de las propiedades, teniendo en cuenta diferentes aspectos para mejor visualización.
-	Análisis de otros datos erróneos con respecto a la ubicación geográfica.
-	Conclusiones del proyecto.

El dataset utilizado en este proyecto corresponde a una muestra de propiedades en venta, publicado en la página de Properati (www.properati.com.ar), en el cual, cada fila es una propiedad en venta.
