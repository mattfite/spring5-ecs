FROM java:8
WORKDIR /
#ADD ./build/install/spring5-app-shadow/lib/spring5-app-1.0-SNAPSHOT-all.jar spring5-app-1.0-SNAPSHOT-all.jar
ADD ./build/libs/spring5-app-1.0-SNAPSHOT-all.jar spring5-app-1.0-SNAPSHOT-all.jar
EXPOSE 8080
#CMD ["java", "-jar", "com.auth0.samples.Main"]
CMD ["java", "-jar", "spring5-app-1.0-SNAPSHOT-all.jar"]
