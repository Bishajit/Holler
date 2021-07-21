## Admin UI
* This will be the interface for the administrators of the application
* It will link to all the microservices in order to manage all aspects of the sysyem
* It will be a secure area only accessible to administrators

## Package UI
* This will be the interface used to request package deliveries
* It will be linked to the Package Management Microservice
* It will be used to register businesses and individuals that initiate package delivery requests

## Package Management
* This will be the MicroService that manages package requests
* It will contain all details about packages
* It will be linked to Invoicing, Messaging and other microservices that require package information.
