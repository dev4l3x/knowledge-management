# Avro vs Protocol Buffers
Ambos son encodings del tipo [[Binary Encoding]] sin embargo tienen algunas diferencias.
A pesar de que ambos usen un schema para codificar los datos y decodificarlos en el destino, [[Avro]] ocupa menos ya que a diferencia de [[Protocol Buffers]] no envía el schema con los datos si no que envía todos los datos uno tras otro (separados solamente por algún byte de control). Protocol Buffers por otra parte envía los datos junto con bytes de control para indicar la correspondencia del dato con la propiedad en el schema (el id) o otras carácteristicas (como si es opcional o requerido).

# Tags
#binary #encoding 