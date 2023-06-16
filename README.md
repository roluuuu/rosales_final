# tercer-entrega-rosales
Este proyecto, se basa en 5 modelos, uno de ventas,uno de pedidos, uno de productos, otro de clientes y por ultimo, uno de reseñas
El modelo de productos, incluye una lista de productos, que a medida que se sumen desde el django admin, se van a mostrar en la pagina productos, bajo el titulo lista de productos, con una pequeña descripcion.
El modelo de clientes , nos va a mostrar los datos del cliente, nombre, email, telefono y direccion. este display de los datos, es temporal porque cuando agregue las reestricciones y los forms, esto no se podra ver mas.
El modelo de pedidos, muestra el producto seleccionado por el cliente, la cantidad y la fecha en la que se pidio.
Por ultimo, el modelo de reseña, este modelo nos permite que el cliente agregue su punto de vista acerca del producto que recibio.
Tiene Sus respectivos login, logout, avatares, registro, delete, create , update y details.
Las apps con las que puede interaccionar el usuario son producto y ventas, despues se crea un cliente por admin, este selecciona un producto, el producto se anota en un pedido y en base a ese pedido, el cliente podria realizar una reseña.
