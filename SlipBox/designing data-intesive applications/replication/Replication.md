# Replication
La replicación consiste en tener una misma copia de los datos en varios nodos. Hay dos maneras de llevarla a cabo
* Asincronamente: En la que un leader envia los datos a los nodos follower pero no espera a la confirmacion.
* Sincronamente: En la que el leader envia los datos a los nodos follower pero esperando confirmacion de que todos han recibido los datos.

En la practica se suele usar un approach intemedio, en el que el nodo leader envia una replicacion sincrona a un nodo esperando confirmacion y a los demas de manera asincrona. De esta manera tenemos la garancia de que al menos los datos estan replicados en un nodo en caso de fallo.

Segun como esten configurados los nodos podemos diferenciar varios tipos de replicacion:
1. [[Leader based replication]]
2. [[Multileader replication]]
3. [[Leaderless replication]]

# Tags
#replication #databases 