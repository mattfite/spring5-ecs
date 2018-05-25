FROM java:8

RUN mkdir -p /usr/src/app
ADD app /usr/src/app

WORKDIR /usr/src/app

EXPOSE 3000

CMD ["java", "-jar", "build/libs/app-1.0-SNAPSHOT-all.jar"]
