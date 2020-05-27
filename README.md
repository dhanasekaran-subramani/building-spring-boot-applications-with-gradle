# building-spring-boot-applications-with-gradle

Initializing the Gradle project

Step 1
mkdir building-spring-boot-applications-with-gradle
cd building-spring-boot-applications-with-gradle

Step 2
$ gradle init --type java-application

Select build script DSL:
Select test framework:
Finally project structure will be created 
Next we need to apply the Spring Boot plugin and define the dependencies

Step 3

Applying the Spring Boot plugin and configuring the dependencies

Step 4

Creating a "Hello Gradle" sample application

Step 6

Building and running the Spring Boot application

$ ./gradlew bootJar
$ java -jar build/libs/gradle-spring-boot-project.jar
$ ./gradlew bootRun
