# [[Servidor DNS]] Local
Este tipo de servidor es aquel al que primero accede un host. Generalmente esta cerca del host y proporcionado por el ISP.
Basicamente es un proxy que actua de intermediario y se encarga de realizar las diferentes peticiones DNS a los [[Servidor DNS Root]], [[Servidor DNS TLD]] y [[Servidor DNS Authoritative]].
Tambien ofrece la posibilidad de cachear las direcciones, por lo que puede devolver la direccion directamente al host si la conoce o puede ser que tenga cacheada alguna direccion de los TLD y no necesite preguntar al [[Servidor DNS Root]].

Se puede ver perfectamente como actua de intemediario en el [[Flujo de una peticion DNS]].

# Tags
#comofuncionadns 