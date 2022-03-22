# Multileader replication
A diferencia de [[Leader based replication]] tenemos varios nodos leader que van a replicar a los follower ademas de a otros nodos leader. Generalmente no compensa usar este approach debido a la complejidad que añade, pero si que hay algunos use cases que se benefician de esto:
* Si tenemos varios datacenter podemos tener un leader por datacenter y que estos leaders se repliquen entre si y a su vez a todos sus followers (que estarian en el mismo datacenter que ellos)
* Tenemos una aplicacion que queremos que funcione offline, tendriamos un nodo leader en cada dispositivo que cuando vuelva a tener conexion replicaria los datos a otros nodos leader en los datacenter.


# Tags
#replication #databases 