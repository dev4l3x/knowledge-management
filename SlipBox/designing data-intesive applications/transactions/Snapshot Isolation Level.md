# Snapshot Isolation Level
En este nivel de [[Isolation]] cuando una transaccion comienza se hace una snapshot de la base de datos en el instante que comienza (o se mantienen varias versiones de ese dato) de tal manera que todas las lecturas se haran sobre esa snapshot (que al ser unica por cada transaccion no se ve afectada por las escrituras de otras transacciones) y las escrituras iran contra la base de datos original adquiriendo un lock.

Este nivel de [[Isolation]] es bastante util cuando tenemos transacciones de lectura bastante grandes como backups o queries analiticas.

# Tags
#databases #transactions 