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

Primeiros passos

01 - local 8080
![alt text](https://github.com/acebeR/usando_quarkus/blob/main/img/8080%20Quarkus.PNG?raw=true)

02 - Terminal
![alt text](https://github.com/acebeR/usando_quarkus/blob/main/img/quarkus%20terminal.PNG?raw=true)

03 - Swagger
![alt text](https://github.com/acebeR/usando_quarkus/blob/main/img/configurando%20o%20swagger.PNG?raw=true)

