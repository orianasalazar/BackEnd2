FROM amazoncorretto:11-alpine-jdk //de que imagen partimos
MAINTAINER Oriana //quien es el dueño 
COPY target/mgb-0.0.1-SNAPSHOT.jar ori-app.jar      //va a copiar el empaquetado a github
ENTRYPOINT ["java","-jar","/ori-app.jar"]       //es la instruccion que se va a ejecutar primero
