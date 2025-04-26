- Esta es una ApiRest hecha con Springboot, destinada a realizar labores fundamentales a nivel administrativo, ventas y control de inventario para una tienda, está dockerizada,
- e incluye persistencia para los datos usando un contenedor con mysql
- Hace CRUD de los clientes, de los productos y de las ventas
  . Permitiendo registrar en una base de datos la información de los clientes que realizan alguna compra, y asociarle a estos los productos que compraron, el valor de la compra, la fecha el día etc.
  . También lleva un control absoluto de todos los productos que entran y salen de la tienda, llevando una cuenta exacta de cada producto, e incluso impidiendo la venta de alguno de estos en caso de que ya no hayan más unidades disponibles.
  . Y cabe recalcar que puedes hacer muchas más operaciones CRUD con las diferentes clases de este proyecto.
   
-NOTA: No olvides leer el archivo .env.example que está en la raíz del proyecto, es escencial leerlo para que la Api funcione sin problema alguno 
