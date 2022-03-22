# Binary [[Encoding]]
Este tipo de encodings son menos verbosos ya que se basan en codificar los datos directamente en una secuencia de bytes, utilizando algunos bytes para indicar tipos o carácteristicas de los datos (bytes de control).

Como los datos se codifican directamente en binario, para ahorrar mas espacio, en lugar de envíar los tipos de datos de cada propiedad y caracteristicas para decodificar en destino, se usan schemas para evitar enviar algunas cosas que tanto el sender como el receiver ya conocen gracias al schema.

Ejemplos de este tipo de encoding son [[Protocol Buffers]] o [[Avro]].

Las principales ventajas frente a los [[Textual Encoding]] son las siguientes:
* Los datos ocupan mucho menos espacio ya que estan codificados directamente en binario (sin usar unicode)
* Se pueden tener checks en tiempo de compilación ya que estos encodings vienen muchas veces con herramientas para generar clases en lenguajes fuertemente tipados.
* El schema sirve de documentación.

# Tags
#encoding #binary