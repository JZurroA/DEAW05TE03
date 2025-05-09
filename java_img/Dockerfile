# Imagen base con Java 21
FROM openjdk:21-jdk-slim

# Directorio de trabajo dentro del contenedor
WORKDIR /app

# Copiar el jar desde la carpeta jar/ al contenedor
COPY jar/springboot-restful-deaw-0.0.1-SNAPSHOT.jar app.jar

# Puerto expuesto (opcional, solo informativo)
EXPOSE 8080

# Comando para ejecutar la aplicación
ENTRYPOINT ["java", "-jar", "app.jar"]