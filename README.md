# Fox-Discovery
The discovery micro service

#Build
mvn -P dev   -DskipTests clean package install deploy

#Run
java -Dspring.profiles.active=development  -jar fox-discovery-ver.jar
