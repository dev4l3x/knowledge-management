# Read Committed Isolation Level
Que una base de datos tenga este nivel de [[Isolation]] quiere decir dos cosas:
* Nunca se va a leer datos modificados por una transaccion que aun no haya hecho commit. Esto es gracias a que se mantienen dos versiones para un mismo valor, la actual que aun no ha sido modificada y la modificado por una transaccion que aun no ha hecho commit.
* Nunca se van a escribir sobre los datos que una transaccion esta modificando y no ha hecho commit aun. Esto se logra gracias a que se adquiere un lock de la base de datos a la hora de escribir.

Una gran ventaja es que como a la hora de leer tenemos dos versiones del dato (la no commiteada y la actual) las lecturas no tienen que ser bloqueadas por las escrituras.
Aunque este nivel de [[Isolation]] no previene de lo que se conoce como [[Read Skew]].

# Tags
#databases #transactions