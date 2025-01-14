<h1>Ejercicio 1. Cálculo de la media y varianza del dataset data_ok.csv</h1>
<ol>
  <li>Calcular mediante paralelización con Spark la media y varianza del dataset data_ok.csv utilizando exclusivamente funciones básicas map/reduce (textFile, reduce, reduceByKey, map, flatmap, filter, count).</li>
  <li>Calcular inicialmente para una sola columna y más tarde para todas las columnas del dataset.</li>
  <li>Verificar que la solucion propuesta es correcta con las funciones rdd.mean() y rdd.stdev().</li>
</ol>
<p>Tal y como se ha comentado en clase, se deben realizar 3 versiones para obtener la nota máxima:</p>
<ul>
  <li>v1: Calcula la media y varianza para la columna 4</li>
  <li>v2: Utilizando las operaciones de vectorizacion de python y arrays de numpy, utilizar la misma estructura de codigo de la version 1 para calcular las medias y varianzas de todas las columnas</li>
  <li>v3: Transforma cada celda del dataset en un elemento (j,v),  donde "j" es la columna de la celda y "v" es el valor de la celda del rdd.
Resuelve el problema con esta nueva estructura del dataset</li>
</ul>

<h1>Ejercicio 2. Clasificador Botnet (versión centralizada y parallelizada)</h1>

Sigue las instrucciones del enunciado "Practica Clasificador ML de botnet" para realizar la práctica. 

Para entregar la práctica, subid:

<ol> 
  <li>Fichero txt con el nombre de los miembros del grupo</li>
  <li>notebook (ipynb) de la version centralizada</li>
  <li>notebook (ipynb) de la version paralela (Spark)</li>
  <li>Trabajo (opcional) en pdf </li>
  <li>Indicad los miembros del grupo en la primera celda de los notebook</li>
</ol>


<em><b>Estas prácticas fueron realizadas por:</b></em>
<ul>
  <li>Daniel Gutierrez San Jose</li>
  <li>Erich González</li>
  <li>Georgelys Marcano</li>
</ul>
<p>Para la materia de <b>Sistemas y Protocolos Aplicados a Internet</b></p>
<em>Septiembre 2024</em>
