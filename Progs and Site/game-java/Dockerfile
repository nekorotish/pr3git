FROM openjdk:11-jdk-slim

WORKDIR /testdir/java

COPY game.java /testdir/java/

RUN javac game.java

ENTRYPOINT ["java", "game"]
