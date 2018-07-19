# demo-service-discovery
Proyecto spring cloud eureka para microservicios

configurar en C:\Windows\System32\drivers\etc\hosts
127.0.0.1       eureka-host1
127.0.0.1       eureka-host2

--para ejecutar los eurekas
>>mvn clean package
java -jar -Dspring.profiles.active=eureka-host1 target/demo-service-discovery-0.0.1-SNAPSHOT.jar

