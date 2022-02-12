# Flujo de una peticion DNS
Cuando un cliente (navegador, ftp) quiere resolver un hostname (por ejemplo www.google.com) tendriamos el siguiente flujo:

1. El cliente envia una peticion al [[Servidor DNS Local]] preguntando por la direccion IP de www.google.com
2. El [[Servidor DNS Local]] si no tiene cacheada la peticion contacta con el [[Servidor DNS Root]] para obtener la direccion del [[Servidor DNS TLD]]. Si este la tiene cacheada puede llamar directamente al [[Servidor DNS TLD]].
3. El [[Servidor DNS Local]] realiza una peticion al [[Servidor DNS TLD]].
4. El [[Servidor DNS TLD]] devuelve un [[Record DNS NS]] correspoindiente al servidor DNS que va a poder resolver la peticion. Este servidor tambien devuelve un [[Record DNS A]] correspondiente al servidor DNS al que tenemos que hacer query.
5. El [[Servidor DNS Local]] realiza la peticion al servidor devuelto en el anterior paso, que lo mas seguro es que se corresponda con el [[Servidor DNS Authoritative]].
6. Este servidor puede devolver un [[Record DNS A]] si el hostname se corresponde con ese o puede resolverlo a traves de los [[Record DNS Cname]] o [[Record DNS MX]].
7. Cuando el [[Servidor DNS Local]] recibe la respuesta le devuelve al cliente la direccion ip correspondiente al hostname que solicito.

Como se puede ver, el [[Servidor DNS Local]] actua como intermediario de toda la complejidad que tiene DNS. Es basicamente un Proxy.


# Tags
#comofuncionadns 