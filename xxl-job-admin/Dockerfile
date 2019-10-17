FROM java:8-jdk-alpine

COPY ./target/xxl-job-admin-2.1.1-SNAPSHOT.jar /usr/app/

WORKDIR /usr/app

RUN sh -c 'touch xxl-job-admin-2.1.1-SNAPSHOT.jar'

ENTRYPOINT ["java", "-Xmx512m", "-Xms512m", "-jar", "xxl-job-admin-2.1.1-SNAPSHOT.jar"]