# SpringCloud

1.>Eureka Service Registry Server – This microservice will provide the service registry 
and discovery server.

2.>Student Microservice – Which will give some functionality based on Student entity. 
It will be a rest based service and most importantly it will be a eureka client service, 
which will talk with eureka service to register itself in the service registry.

3.>School Microservice – Same type as of Student service – only added feature is that 
it will invoke Student service with service look up mechanism. 
We will not use absolute URL of student service to interact with that service.
