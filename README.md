# DockerHelloWorld


This is sample project for Hello World which contains docker file to test on docker container.
It uses java 11.


![image](https://github.com/chaitalishah/DockerHelloWorld/assets/13629726/22b82e57-2d32-4175-9e9e-3a03a6963357)


**Add below pom.xml**
Add below pom.xml
<plugin>
<groupId>org.apache.maven.plugins</groupId>
<artifactId>maven-jar-plugin</artifactId>
<version>3.2.0</version>
<configuration>
<archive>
<manifest>
<addClasspath>true</addClasspath>
<classpathPrefix>lib/</classpathPrefix>
<mainClass>com.example.App</mainClass>
</manifest>
</archive>
</configuration>
</plugin>![image](https://github.com/chaitalishah/DockerHelloWorld/assets/13629726/78df2cef-29be-409b-9064-865570fcea9b)


**Sample Docker File for maven project.**

FROM adoptopenjdk:11-jre-hotspot
WORKDIR /app
COPY target/my-app-1.0-SNAPSHOT.jar app.jar
CMD ["java", "-jar", "app.jar"]![image](https://github.com/chaitalishah/DockerHelloWorld/assets/13629726/50d35bd9-e3da-4bb0-9d55-fd7c91f22262)

