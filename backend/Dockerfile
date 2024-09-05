FROM openjdk:21-jdk
WORKDIR /app
EXPOSE 8080
COPY target/PortefeuilleFinancier-0.0.1-SNAPSHOT.jar /app/PortefeuilleFinancier.jar
ENTRYPOINT ["java", "-jar", "PortefeuilleFinancier.jar"]
