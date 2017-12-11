FROM java:8
VOLUME /tmp 
COPY spring-boot-two-0.0.1-SNAPSHOT.jar spring-boot-two.jar
RUN sh -c 'touch /spring-boot-two.jar'
EXPOSE 8080
ENV JAVA_OPTS=""
ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/spring-boot-two.jar"]