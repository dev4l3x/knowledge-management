# Property Graphs
Representación que usan las bases de datos basadas en graphos para el modelado de datos. Se basa en tener un documento compuesto por:
* Un identificador uno para cada entidad de ese vertice
* Un set de relaciones que entran al vertice
* Un set de relaciones que salen del vertice
* Un conjunto de propiedades adicionales para representar la entidad.

Cada relación consiste a su vez de un documento con las siguientes propiedades:
* Un identificador único para esa relación. Este identificador se usaría posteriormente en el set de relaciones de los documentos de los vertices.
* Un vertice en el que empieza la relación (tail vertix) y un vertice en el que acaba la relación (head vertix).
* Un label que describe la relación entre los dos vértices.
* Una conjnto de propuedades para representar la relación.

# Tags
#databases #graphs 