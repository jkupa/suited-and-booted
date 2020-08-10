# suited-and-booted
CS3

Controller
•	This controller exposes the url that receives requests from the graphQL app
o	Serves as the entry point to the API
•	@RestController is a specific type of controller which is a combination of @Controller and @ResponseBody
o	@ResponseBody – the body of the reponse to the request will consist of the returned value of the designated method

WiringInstruction Fetcher
•	Pulls data out from the tsmDirWiringInstruction table in QuasarDB
•	Created a WiringInstruction @Repository
o	Extends JPARepository (contains API for basic CRUD operations and sorting)
•	Built a WiringInstruction Data Fetcher with the capabilities of retrieving a particular WiringInstruction if provided the WIid or fetching all WiringInstructions
•	Created a method in the GraphQL service class that creates the runtime wiring for the wiringinstructions datafetcher
•	Configure @PostMapping to execute getWiringInstructions
