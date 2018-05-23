FROM java:8

#RUN yum -y update
#RUN curl --silent --location https://rpm.nodesource.com/setup_6.x | bash -
#RUN yum -y install nodejs

RUN mkdir -p /usr/src/app
ADD app /usr/src/app

WORKDIR /usr/src/app

EXPOSE 3000

CMD ["java", "-jar", "./build/libs/spring5-app-1.0-SNAPSHOT-all.jar"]
