# ms1-service-registry




Start application in below order
1. Service-Registry
2. cloud-config-server
3. API-Gateway (cloud-gateway)
4. dept.service
5. usr service
6. hystrix-dashboard



--> Check Eureka all services are up or not http://localhost:8761/
--> check API-Gateway is working or not http://rahul-yoga:9191/actuator
--> Get the Stream http://rahul-yoga:9191/actuator/hystrix.stream  and push to Hystrix monitor http://rahul-yoga:9295/hystrix and start monitoring


to check services are working or not 
http://localhost:9001/swagger-ui.html#/
http://localhost:9002/swagger-ui.html#/

or check using API Gateway
http://localhost:9191/users/1
http://localhost:9191/departments/1
