# Hash Index en DB
Mantenemos en memoria un HashMap donde almacenamos las claves del índice y los valores que se corresponden con el documento en si o con la dirección de memoria al donde se encuentra el documento en disco.

El principal problema de este tipo de indice es que tenemos que almacenar todas las claves y valores en memoria y que no permite de forma eficiente hacer queries por rangos de valores (es decir queries que piden un valor del indice entre un rango)

# Tags
#databases #index 