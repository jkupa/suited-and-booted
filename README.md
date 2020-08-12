# suited-and-booted
CS3

As you can see from our agenda, we will begin by introducing you to our team, followed by an explanation our teams business problem. Next we will discuss our approach to the solution followed by a brief walkthrough of our project. We will then close with  our project  demo followed by  a brief Q&A

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
•	plugin execution framework / build automation tool used to mange projects
Aspects of the Spring Framework  
•	Spring Boot to launch application
•	Spring Data JPA, utilizing its built in query methods through annotations 
Google Rejoiner Project 
•	Acts as the intermediary between GraphQL and gRPC
•	supports creation of GraphQL server on top of gRPC microservices
•	generates GraphQL types from Proto definitions, populates request Proto based on GraphQL query  parameters (protos generated via BlackRock plugin)
Docker
•	lightweight and deploys applications
•	Unfortunately we weren’t able to get the proper security clearances to implement docker for our presentation, nonetheless we’ll still have a great demo for you all at the end of our slideshow! :)

