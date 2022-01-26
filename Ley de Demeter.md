# Ley de Demeter
Un objeto solo debe relacionarse con sus objetos inmediatios. Esto es a fin de no acoplarse a más clases en la cadena.

```java
promotion.getPromotionCode("CODE").getStore().getId()
```

Por ejemplo aqui estariamos acoplados directamente a la estructura interna de promotion code y a su vez de store, y si estos cambian nos obliga a modificar la clase cuando no debería ser así. En su lugar debería proporcionarse el acceso en el objeto directamente relacionado desacomplandonos asi en este caso de `PromotionCode` y de `Store`.

```java
promotion.getStoreIdForPromotionCode("CODE")
```


# References
[Ley de Demeter - Adictos al trabajo](https://www.adictosaltrabajo.com/2015/07/24/ley-de-demeter/)



# Tags