# BazarAPI
API realizada con Spring Boot la cual se encarga de administrar las ventas y los clientes de un bazar.

Contiene un CRUD para clientes, ventas y productos. También contiene endpoints para crear detalles de venta. Cada vez que se cree un detalle de venta, se va a eliminar la cantidad de productos comprados y se sumará el total del detalle (precio del producto multiplicado por la cantidad comprada) al total de la venta asociada.

Se utilizó Java 17, Spring Boot, JPA, MySQL y una arquitectura multicapas. Para probar los endpoints se utilizó Postman (las collections de postman se encuentran en el repositorio).
