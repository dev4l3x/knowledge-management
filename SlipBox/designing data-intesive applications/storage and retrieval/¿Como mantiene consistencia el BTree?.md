# ¿Como mantiene consistencia el BTree?
Como los BTree sobrescribe las páginas a la hora de actualizar el índice, usa un write-ahead log el cual es un [[Append Only]] file que se puede usar para restaurar en caso de que se produzca un crasheo a la hora de escribir en disco.

# Tags
#algorithms #databases #index 