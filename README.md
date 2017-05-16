## Spring Boot Hibernate

### Technologies
JPA, Hibernate, H2, Spring Boot <br />


### Data Model
Entities: <br />
Note, Tag <br />

Relations: <br />
Note:Tag = m:n <br />

Tables in Database: <br />
note, tag, note_tags  <br />

Database Tables are created at application start <br />
Insert of data via file 'import.sql' <br />


### Steps
##### Build and Run Application
via spring-boot-maven-plugin: <br /> 
*mvn clean compile*  <br />
*mvn spring-boot:run*  <br />

##### Build jar, Run jar
*mvn package* <br />
*java -jar target/jar-name.jar* <br />

##### Access Application
*http://localhost:8080*


### Original Source:
https://github.com/spring-projects/spring-boot/tree/master/spring-boot-samples


