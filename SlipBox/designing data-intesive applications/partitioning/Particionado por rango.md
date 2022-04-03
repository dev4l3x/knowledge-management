# Particionado por rango
En este tipo de particionado asignariamos a cada nodo un rango de valores que puede contener. De esta manera tenemos los datos ordenados (tanto los nodos como dentro de los nodos) y podriamos hacer queries por rango bastante efectivas.
El principal problema que tenemos con este tipo de particionado es que puede ocurrir lo que se conoce como [[Skew en DB]] y [[Hot Spots en DB]].
Por eso es importante particionar bien los datos dependiendo en la naturaleza de los mismos y de nuestra aplicación, es decir, cada aplicación necesitara un particionado independiente a la naturaleza de sus datos.
Para la ordenación dentro del particionado se suelen usar [[SSTables]] y [[LSM Tree]].

# Tags
#partitioning #databases  #sharding 