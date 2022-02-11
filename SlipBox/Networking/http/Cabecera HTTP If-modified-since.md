# Cabecera HTTP If-modified-since
Esta cabecera indica al servidor que si el objeto no ha sido modificado desde la fecha indicada devuelva un `304 Not Modified` y si a sido modificado que devuelva el objeto en si. 
Esto es especialmente util cuando se utiliza una cache para las peticiones, para saber así si el objeto cacheado es invalido o no. 


# References
[[HTTP Header]]


# Tags
#http #httpheaders 