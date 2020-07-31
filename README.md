# Zipkin-distributed-tracing-server

add a dependency in all all these microservices

<dependency>
			<groupId>org.springframework.cloud</groupId>
			<artifactId>spring-cloud-starter-sleuth</artifactId>
		</dependency>
		<dependency>
			<groupId>org.springframework.cloud</groupId>
			<artifactId>spring-cloud-sleuth-zipkin</artifactId>
		</dependency>
    
    no other configuration is required other than dependencies
    
    it is very difficult to check and maintain each of the microservice logs so spring-cloud introduced a concept called
    centralized information logs where we can store all the information in one place that is Zipkin-distributed-
    tracing-server with rabbitMQ
    
    Zipkin-distributed-tracing-server -- what happened with the specific service request call. and can able
    to track it across all the different microservices
    
    if there was a problem in specific microservice we can go particular thing and find out 
    more details about what has happened with this specific request
