# Leaderless replication
Seria como una configuracion [[Multileader replication]] en la que todos los nodos son leader. Es decir, podemos escribir a varios nodos a la vez y leer de cualquiera de ellos.
Aqui la replicacion se produce por el propio cliente que envia la escritura a varios nodos simultaneamente o a traves de un nodo coordinador el cual se encarga de replicar los datos entre los nodos.

A la hora de tener los datos actualizados, estos llevan un numero de version, y cuando la version es antigua el nodo coordinador actualiza los datos en ese nodo. Tambien es posible tener un proceso en background que vaya comprobando las versiones en los nodos con el objetivo de actualizar los datos cuando estos son antiguos.

# Tags