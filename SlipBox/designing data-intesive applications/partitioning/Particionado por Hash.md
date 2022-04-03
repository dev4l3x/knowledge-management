# Particionado por Hash
En este tipo de [[Partitioning o Sharding]] utilizariamos una función hash sobre la key de los datos para decidir en que partición situarlos. De esta manera podemos distribuir los datos de manera uniforme independientemente de la naturaleza de los mismos o de la aplicación.
*El principal problema de este approach es que las queries por rango no son muy efectivas, ya que para encontrar los valores deseados hay que buscar en todos los nodos al no estar los datos ordenados.*

# Tags
#sharding #partitioning #databases 