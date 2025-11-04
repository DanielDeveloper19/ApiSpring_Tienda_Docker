🏪 Store Management API

A complete RESTful backend system built with Spring Boot that handles administration, sales, and inventory management for retail stores.
Fully containerized with Docker, featuring persistent data storage through a MySQL container for reliability and scalability.

The API enables full CRUD operations for customers, products, and sales — allowing stores to:

Register and manage customer profiles

Record and associate purchases with customers, products, prices, and dates

Maintain precise real-time control of product stock

Automatically prevent sales when stock is depleted, ensuring data consistency and business logic integrity

Designed with a modular architecture, it supports additional CRUD operations across multiple entities, making it easy to extend and integrate with other services such as billing, analytics, or external inventory systems.

Tech Stack: Java, Spring Boot, MySQL, Docker, REST API, JPA/Hibernate

-NOTE: Do not forget to read the .env.example file that is in the root of the project, it is essential to read it for the Api to work without any problem. 

- Esta es una ApiRest hecha con Springboot, destinada a realizar labores fundamentales a nivel administrativo, ventas y control de inventario para una tienda, está dockerizada
 e incluye persistencia para los datos usando un contenedor con mysql
- Hace CRUD de los clientes, de los productos y de las ventas
  . Permitiendo registrar en una base de datos la información de los clientes que realizan alguna compra, y asociarle a estos los productos que compraron, el valor de la compra, la fecha el día etc.
  . También lleva un control absoluto de todos los productos que entran y salen de la tienda, llevando una cuenta exacta de cada producto, e incluso impidiendo la venta de alguno de estos en caso de que ya no hayan más unidades disponibles.
  . Y cabe recalcar que puedes hacer muchas más operaciones CRUD con las diferentes clases de este proyecto.
   
-NOTA: No olvides leer el archivo .env.example que está en la raíz del proyecto, es escencial leerlo para que la Api funcione sin problema alguno 
