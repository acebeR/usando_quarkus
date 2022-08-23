Tecnologias
- Java 11.0.16
- Quarkus
- Maven

Para criar o projeto Quarkus
- ./mvnw compile quarkus:dev
Configurar o Swagger
- cmd /c .\mvnw.cmd quarkus:add-extension -Dextensions="io.quarkus:quarkus-smallrye-health,io.quarkus:quarkus-smallrye-openapi" -f "c:\Users\acebe\Documents\Git\usando_quarkus\usando_quarkus\pom.xml"
Configurar o ID Conection
- cmd /c .\mvnw.cmd quarkus:add-extension -Dextensions="io.quarkus:quarkus-oidc" -f "c:\Users\acebe\Documents\Git\usando_quarkus\usando_quarkus\pom.xml"
