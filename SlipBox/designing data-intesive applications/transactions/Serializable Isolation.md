# Serializable Isolation
Es el nivel de [[Isolation]] mas fuerte de todos, ya que garantiza que las transacciones tendran el mismo resultado que si se ejecutasen secuencialmente, es decir, soluciona todos los problemas que conllevan ejecutar transacciones concurrentemente.

Tenemos diferentes tipos de implementar este nivel de [[Isolation]]:
* [[Serial Execution]]
* [[Two Phase Locking (2PL)]]
* [[Serializable Snapshot Isolation (SSI)]]

# Tags
#databases #acid #transactions 