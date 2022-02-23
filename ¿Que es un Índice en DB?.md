# ¿Que es un Índice en DB?
Como las bases de datos tienen que ir a buscar a disco constantemente los datos para poder hacer comprobaciones sobre los datos de una colección o tabla tendriamos que leerlos todos de disco y posteriormente comprobar si cumple las condiciones para seleccionarlo.
Para evitar tener que llegar a buscar en disco (ya que es bastante costoso) se utilizan indices, que son metadatos que indican donde se encuentran en disco los datos reales (o los contienen directamente).
Al añadir un índice mejoramos los tiempos de lectura pero empeoramos los de escritura, ya que no solo tenemos que escribir los nuevos datos sino actualizar el índice.

# Tags
#databases 