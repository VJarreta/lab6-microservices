##The two microservices are running and registered (two terminals, logs screenshots).
	- Microservice at port 2222:
![microservice:2222](screenshots/1_1.PNG)

	- Microservice at port 3333:
![microservice:3333](screenshots/1_2.PNG)


##The service registration service has the two microservices registered (a third terminal, dashboard screenshots)
	- Microservice registration at port 1111:
![microservice:1111](screenshots/2_1.PNG)

	- Dashboard:
![microservice:1111](screenshots/2_2.PNG)

##A second account microservice is running in the port 4444 and it is registered (a fourth terminal, log screenshots).
    - New account microservice at port 4444:
![microservice:4444](screenshots/3_1.PNG)

    - Dashboard:
![microservice:4444](screenshots/3_2.PNG)


##A brief report describing what happens when you kill the microservice with port 2222. Can the web service provide information about the accounts? Why?
	- Once the account services dies (port 2222), Eureka still has an instance of the same service registered and running on port 4444 and the service keeps working.