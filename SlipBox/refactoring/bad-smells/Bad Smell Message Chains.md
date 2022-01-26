# [[Bad Smell]] Message Chains
Tenemos un objeto que accede a otro objeto a traves de varias llamadas encadenadas. Por ejemplo:

```java
getObjA().getObjB().getObtC()
```

Haciendo esta cadena, estariamos accediendo al objeto C a traves del objeto B, que a su vez este se accede a traves del objeto A.

Básicamente esto viola la [[Ley de Demeter]].
# References



# Tags