FROM openjdk:11-jdk
VOLUME /tmp
ADD target/wontak-hello-msa-spring-boot-0.0.1-SNAPSHOT.jar app.jar
ENV JAVA_OPTS=""
ENTRYPOINT exec java $JAVA_OPTS -Djava.security.egd=file:/dev/./urandom -jar /app.jar
