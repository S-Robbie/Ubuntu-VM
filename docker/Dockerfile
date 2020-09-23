FROM openjdk:8u232-jre-slim-buster
LABEL maintainers "Robin S, srobin.2310@gmail.com"
WORKDIR /app
COPY fitnesse-standalone.jar .
ENTRYPOINT ["java", "-jar", "fitnesse-standalone.jar", "-p"]
CMD ["80"]
EXPOSE 80
VOLUME /app.FitNesseRoot