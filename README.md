# SwaggerUI-
How to enable swagger UI for the Springboot application


Just check the pom.xml has one dependecy of - <artifactId>springdoc-openapi-starter-webmvc-ui</artifactId>

and the app.props has - springdoc.swagger-ui.path=/swagger-ui.html

link of swagger ui - http://localhost:8080/swagger-ui/index.html which is of format - http://server:port/context-path/swagger-ui.html


Adding to docker. First write Dockerfile (Build the application, and Run the application).

After build the image using this Dockerfile -  docker build -t atul-springboot-app .

lastly we can run this image on our docker container - docker run -p 8080:8080 atul-springboot-app

You can view the runnning container by - docker ps 

if you want to access running container shell - docker exec -it <container_id> /bin/sh


to stop container -  docker stop <container_id>  and to remove - docker rm <container_id>
