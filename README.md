# Desafio_Woowup

Ejercicio 1.

Haciendo un GET al siguiente endpoint https://jumbo.vtexcommercestable.com.br/api/catalog_system/pub/products/search?_from=0&_to=49

a) Identificar el producto con mayor precio de marca “Cuisine & Co”
b) Exportar en un archivo CSV un listado de los 50 productos con las siguientes columnas:
* productId
* nombre
* marca
* precio de lista
* precio de oferta
* + cinco campos que consideres serían los más importantes para utilizar en Marketing a través de una campaña de email.

El archivo CSV debe estar codificado en UTF-8 y usando punto y coma (”;”) como separador.

c) Obtener el link a la documentación técnica de ese endpoint.


Ejercicio 2.

Suponiendo que tenemos una tabla llamada Products que contiene información sobre productos de una marca. La tabla tiene las siguientes columnas:

- sku (identificador único del producto) [VARCHAR]
- nombre (nombre del producto) [VARCHAR]
- categoria (categoría del producto) [VARCHAR]
- precio (precio del producto) [FLOAT]
- stock (cantidad disponible en stock) [INT]
- fecha_update (fecha de última actualización ‘YYYY-MM-DD HH:mm:ss’) [DATETIME]

a) Escribir la query mediante la cual se seleccionan todos los productos de la categoría 'Electrónicos'.

b) Escribir la query mediante la cual se seleccionan todos los productos que pertenecen a la categoría 'Electrónicos' y tienen un precio mayor a $50.000.

c) Escribir la query mediante la cual se seleccionan todos los productos con stock mayor a 0 y cuya fecha de actualización fue en enero de 2024.
