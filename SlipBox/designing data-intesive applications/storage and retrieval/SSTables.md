# SSTables (Sorted String Tables)
Es una manera de almacenar los datos en disco para las bases de datos (en concreto las NoSQL) o para almacenar los indices creados en las bases de datos.

Se basan en la carácteristica [[Append Only]]. Tenemos segmentos de datos almacenados en disco los cuales estan ordenados según algún criterio. Periodicamente es necesario realizar la técnica de compactación y mergeo para que los datos no crezcan indefinidamente.

Para insertar los datos ordenados este tipo de almacenamiento mantiene en memoria un arbol AVL (conocido como memtable) que cuando llega a un tamaño determinado se guarda como un nuevo segmento en disco.

# Tags
#databases 