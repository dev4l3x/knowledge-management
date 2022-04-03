# Serial Execution
Consiste en ejecutar las transacciones en serie, es decir, tendremos un unico thread que sera el encargado de ejecutar todas las transacciones una tras otra. Por lo que en este nivel de [[Isolation]] no se podran ejecutar transacciones concurrentemente.

Como esto puede suponer un gran problema de rendimiento no se permiten transacciones que impliquen varias peticiones http entre cliente y servidor (ya que mete mucho tiempo adicional y una transaccion tiene que esperar por otra) por eso generalmente se obliga a que las transacciones se definan como procedures en la base de datos.

Ademas como solo se va a ejecutar una unica transaccion lo ideal es que los procedures definidos sean lo mas pequenos posibles para que no se bloqueen.

Se basa en el algoritmo de concurrencia [[Pessimistic Locking]].

# Tags
#transactions #databases #acid 