
220219: Spring Boot: Rest: Add Controller
//ref: url: https://spring.io/guides/gs/serving-web-content/

Easiest way to run the Application is: 
	- On project SpringMvc > Run as > Java Application 
	- url: http://localhost:8080/greeting
		- output: Hello, world!
	- url: http://localhost:8080/greeting?name=Paul
		- output: Hello, Paul!
		
Other way to run the Application: Command prompt 220219
	- cd: to the directory where your application is located. 
		- pom.xml would be located there 
	- exec: mvn clean spring-boot:run 
		- will run your application 
	- curl: can be used to call any rest webservices if you have any 
	
	- Alternatively: you can use the Spring Initializer maven wrapper 
		- exec: ./mvnw clean spring-boot:run
		- more