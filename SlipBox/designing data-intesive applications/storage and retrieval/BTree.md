# BTree
Este algoritmo se basa en almacenar en disco páginas de tamaño fijo simulando asi como funcionan los discos que almacenan los datos en sectores. Cada página contiene una serie de referencias y nodos que indican que rangos contiene esa referencia. Por ejemplo, una referencia que se encuentra entre los valores 100 y 200 indica que todas las referencias y valores de las paginas hijas van a tener las keys entre esos rangos.

![[BTree.png]]

Si vamos recorriendo todas las referencias del árbol llegaremos a las páginas raíz, las cuales son las que contienen la key y el valor para esa key. El índice puede contener todos los datos en el valor del propio indice, lo que se conoce como [[Covering Index]] o puede contener la dirección de memoria donde se encuentran los datos almacenados (ese lugar se conoce como heap).

# Tags
#databases #index 