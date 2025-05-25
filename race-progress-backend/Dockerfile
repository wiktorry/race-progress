FROM maven:3.9.9-amazoncorretto-17-alpine
COPY . /race
WORKDIR /race
RUN mvn package -DskipTests
ENTRYPOINT ["java","-jar","/race/target/race-app.jar"]