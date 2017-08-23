FROM java
VOLUME /temp
ADD cloud-eureka-1.0-SNAPSHOT.jar /discovery.jar
EXPOSE 8761
RUN bash -c "touch /discovery.jar"
ENTRYPOINT ["java","-jar","/discovery.jar"]

