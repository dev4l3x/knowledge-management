# Lost update problem
Se da cuando dos transacciones leen un **mismo** valor y una de ellas lo modifica antes de que la otra acabe, dando lugar a que la que no acabo tenga una lectura inconsistente y por tanto si guarda los datos deje la DB en un estado incosistente. Una transaccion sobreescribe los datos de la otra sin tener en cuenta la modificacion que ha hecho.
Hay varias maneras de solucionarlo:
* Utilizando escrituras atomicas, es decir, enviar una unica query que modifique los datos directamente en lugar del ciclo read-update-write.
* Actualizar en una transaccion, adquiriendo un lock mediante un SELECT.
* Detectando automaticamente lost updates con [[Snapshot Isolation Level]]
* Comparando el valor que queremos guardar con el valor que esta actualmente guardado y si por ejemplo un numero de control de version no coincide quiere decir que otra transaccion ha modificado el objeto.


# Tags
#databases #transactions 