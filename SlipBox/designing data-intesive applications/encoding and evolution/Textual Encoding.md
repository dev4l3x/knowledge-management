# Textual [[Encoding]]
Este tipo de encoding se basa en utilizar Unicode para codificar los datos en una manera legible para los humanos.

Ejemplos son CSV, JSON o XML, en los cuales tenemos los datos legibles pero a la hora de enviarlos de envían como un byte array codificados con Unicode o cualquiera de sus variantes.

El principal problema de este tipo de encoding es que los datos a enviar o almacenar ocupan bastante más espacio ya que hay caracteres que se usan para que un humano lea mejor los datos pero que a la hora de enviar no son útiles pero se codifican igual (las llaves por ejemplo). Para solucionar este problema se usa los [[Binary Encoding]]

# Tags
#encoding 