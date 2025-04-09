FROM openjdk:17-jdk-alpine
WORKDIR /app
COPY /src/Main.java /app/Main.java
COPY /quotes.txt /app
RUN javac Main.java
CMD ["java","Main"]
