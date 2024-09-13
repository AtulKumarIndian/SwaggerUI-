# SwaggerUI-
How to enable swagger UI for the Springboot application


Just check the pom.xml has one dependecy of - <artifactId>springdoc-openapi-starter-webmvc-ui</artifactId>

and the app.props has - springdoc.swagger-ui.path=/swagger-ui.html

link of swagger ui - http://localhost:8080/swagger-ui/index.html which is of format - http://server:port/context-path/swagger-ui.html