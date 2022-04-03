# Serializable Snapshot Isolation (SSI)
Es un nuevo algoritmo que buscar solucionar los problemas de rendimiento de [[Serial Execution]] y [[Two Phase Locking (2PL)]] debido al overhead que supone el manejo de los locks.
El algormitmo se basa en utilizar [[Snapshot Isolation Level]] con el anadido de que cuando se hace commit se comprueba si se ha producido alguna condicion no desead como [[Lost update problem]], [[Write Skew]] o [[Read Skew]]. En el caso de que se haya producido se aborta la transaccion y la aplicacion tendra que reintentarla nuevamente.

Este algoritmo se basa en el algoritmo de concurrencia [[Optimistic Locking]].

# Tags
#databases #acid #transactions 