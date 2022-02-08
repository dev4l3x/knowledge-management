# Varias conexiones simultaneas a un mismo host
Es posible establecer varias conexiones simultaneas a un mismo host desde un único client utilizando puertos distintos del client. De esta manera al tener un `source port` distinto formaran [[Socket]] distintos.
Por ejemplo si tenemos un servidor HTTP en puerto 80 para la dirección X, y un cliente en la dirección Y, podríamos establecer tantas conexiones como puertos libres tenga el cliente.

# References



# Tags
#tcp #peticionesconcurrentes 