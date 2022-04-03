# Two Phase Locking (2PL)
Es el metodo mas clasico que implementan las bases de datos para dar lugar a la [[Serializable Isolation]].
Con este metodo todas la transacciones van a adquirir un lock existiendo dos tipos de este:
* Shared Lock: Lock que se adquiere en la lectura de los datos y puede haber varios de este tipo sobre los mismos datos (esto es para que las lecturas no se bloqueen entre si)
* Exclusive Lock: Lock que se adquiere en la escritura de los datos. Si un obejto tiene este tipo de lock solo podra tener este (no puede tener mas locks exclusivos ni shared).

Es importante mencionar que si una transaccion adquiere un shared lock y luego quiere escribir, tiene que hacer upgrade de ese lock a uno exclusivo (siempre y cuando sea posible, sino tendra que esperar).

Se basa en el algoritmo de concurrencia [[Pessimistic Locking]].

# Tags
#databases #transactions #acid 