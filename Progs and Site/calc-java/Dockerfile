FROM openjdk:11-jdk-slim

WORKDIR /testdir/java

COPY calc.java /testdir/java/

RUN javac calc.java

ENTRYPOINT ["java", "calc"]
