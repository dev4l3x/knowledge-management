# Read Skew
Cuando tenemos una transaccion que lee un valor y entre que lo lee y lo escribe hay otra transaccion que modifica el dato (haciendo commit) da lugar a que la lectura de la primera transacccion no sea valida ya que el valor previamente leido se ha modificado.

# Tags
#databases #transactions 