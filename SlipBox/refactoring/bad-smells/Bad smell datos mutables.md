# [[Bad Smell]] datos mutables
El principal problema de los datos mutables es cuando tienen un scope muy grande, es decir, se pasan de una función a otra hasta el punto de que ya no sabemls exactamente por donde pasa.

El problema con que sean mutables y tengan un scope tan grande es que puede ser que alguna función de todas a las que se le pasa haga más de lo que esperamos y modifique el objeto sin que lo sepamos, dando lugar a comportamientos no esperados. 

# References



# Tags