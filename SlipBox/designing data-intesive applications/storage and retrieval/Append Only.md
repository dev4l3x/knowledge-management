# Append Only
Es una caracteristica que indica que a la hora de insertar nuevos datos no se van a sobrescribir si no que se van a insertar en un lugar nuevo. Esto es para poder volver atras en caso de que sea necesario.

Como siempre se añade y nunca se elimina o reemplaza es importante aplicar una serie de técnicas para que el tamaño en disco no crezca indefinidamente:

* **Compactación**: Consiste en eliminar los duplicados, es decir, eliminar los datos que no son los últimos.
* **Mergeo**: En caso de que los datos se almacenen en disco en chunks o segmentos, es necesario mergear los segmentos despues de una compactación para que no se fragmenten los datos y nos quedemos con muchos ficheros muy pequeños.

# Tags