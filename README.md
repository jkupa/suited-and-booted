# suited-and-booted
CS3

Justin Kupa, Franklin & Marshall College (Lancaster, PA)
Flexible API Model w/ GraphQL over gRPC
Fav Moment: Bonding with the team
	Talking to Ragesh during his  FTO
	Communication w fellow interns and forming solace over our struggles
	And of course who could forget the game nights :/

Business Problem:
In 2019 BlackRock made the major acquisition of eFront providing Aladdin the opportunity to advance and expand their breadth in Alternatives industry. As a result of this accomplishment, we were tasked with the integration of the new eFront technology into the existing Aladdin ecosystem. Through this process our end-goal was to build a flexible API that enables data mobility and synchronization between QuasarDB, which holds preexisting BlackRock Alternative Investment information, and the newly acquired eFront technology.

In order to transform our goal into a reality…:
We utilized the powerful and efficient GraphQL technology to query data from the QuasarDB
We then exposed the retrieved data over HTTP (REST) and gRPC Server endpoints for client access



Technology Used:
Java
•	We all know Java, you either love or hate it and we chose to love this  programming language for our project
GraphQL
gRPC
Maven 
•	plugin execution framework / build automation tool
Spring Framework  
•	Spring Boot to launch application
•	Spring Data JPA lets us avoid building custom SQL queries (built-in query methods)
Hibernate Framework 
•	object-relational mapping tool for Java; used to map the entities we created (WI, Product, Bank) to tables in QuasarDB
Google Rejoiner Project 
•	supports creation of GraphQL server on top of gRPC microservices
•	generates GraphQL types from Proto definitions, populates request Proto based on GraphQL query  parameters (protos generated via BlackRock plugin)
Docker
•	uses OS-level virtualization to enable deployment of applications as lightweight, self-sufficient containers
