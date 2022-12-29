# Banana Matata microservices

* Banana Matata is a microservices architecture for a simple web application.

* The application is a simple online store for bananas.

* The application is composed of 3 microservices:

  * banana-order: the order microservice
  * banana-delivery: the delivery microservice
  * banana-farm: the farm microservice 
  * banana-inventory: the inventory microservice 
* The banana-order microservice is responsible for managing orders.
* The banana-delivery microservice is responsible for managing deliveries.
* The banana-farm microservice is responsible for managing farms.
* The banana-inventory microservice is responsible for managing inventory.

* The banana-order microservice is a REST API that exposes the following endpoints:

  * GET /orders: returns all orders
  * GET /orders/{id}: returns the order with the given id
  * POST /orders: creates a new order
  * PUT /orders/{id}: updates the order with the given id
  * DELETE /orders/{id}: deletes the order with the given id
* The banana-delivery microservice is a REST API that exposes the following endpoints:
    
      * GET /deliveries: returns all deliveries
      * GET /deliveries/{id}: returns the delivery with the given id
      * POST /deliveries: creates a new delivery
      * PUT /deliveries/{id}: updates the delivery with the given id
      * DELETE /deliveries/{id}: deletes the delivery with the given id

* The banana-farm microservice is a REST API that exposes the following endpoints:
     
        * GET /farms: returns all farms
        * GET /farms/{id}: returns the farm with the given id
        * POST /farms: creates a new farm
        * PUT /farms/{id}: updates the farm with the given id
        * DELETE /farms/{id}: deletes the farm with the given id

* The banana-inventory microservice is a REST API that exposes the following endpoints:

            * GET /inventory: returns all inventory
            * GET /inventory/{id}: returns the inventory with the given id
            * POST /inventory: creates a new inventory
            * PUT /inventory/{id}: updates the inventory with the given id
            * DELETE /inventory/{id}: deletes the inventory with the given id

Thanks copilot for generating the docs :D