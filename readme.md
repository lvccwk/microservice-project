#cd pom.xml location (servicea,serviceb,eureka-server)
mvn clean package

#server start
java -jar eureka-server/target/_.jar
java -jar service-a/target/_.jar
java -jar service-b/target/\*.jar

Action:
Change Spring Boot version to one of [3.4.x]
Or set spring.cloud.compatibility-verifier.enabled=false
