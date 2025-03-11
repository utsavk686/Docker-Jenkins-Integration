FROM eclipse-temurin:19
LABEL maintainer="yaswanth@gmail.com"
WORKDIR /app
COPY target/springboot-mysql-docker-latest.jar springboot-docker-demo-1.jar
ENTRYPOINT ["java","-jar","springboot-docker-demo-1.jar"]