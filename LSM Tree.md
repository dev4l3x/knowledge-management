# LSM Tree (Log Structured Merge Tree)
Es un algoritmo que se utiliza en las bases de datos para crear índices. Se basa en almacenar los datos utilizando [[SSTables]] y posteriormente mantener en memoria una tabla con sparse index, es decir, con indices que apuntan a determinados segmentos.
Al ser sparse index si buscamos un valor que no esta en la tabla en memoria pero se encuentra entre los valores de dos indices, tenemos que buscar todos los segmentos que se encuentran etre esos dos indices.

Es muy similar a [[Hash Index en DB]] con la diferencia de que al almacenar los datos en segmentos ordenados no tenemos que tener todos los indices en memoria cargados, solo tenemos algunos para establecer unos rangos.

Una gran ventaja de este algoritmo es que podemos comprimir los datos antes de guardarlos en disco ya que solo vamos a necesitar leer unos cuantos segmentos por cada query.


# Tags