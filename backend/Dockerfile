FROM openjdk:17
WORKDIR /app
COPY . /app
RUN ./mvnw clean package -DskipTests
CMD ["java", "-jar", "target/mapeamento-0.0.1-SNAPSHOT.jar"]
