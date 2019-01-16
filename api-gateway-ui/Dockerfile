FROM openjdk:8-jre-alpine
ENV APP_FILE spring-petclinic-api-gateway-2.0.7.jar
ENV APP_HOME /usr/app
EXPOSE 7000
COPY target/$APP_FILE $APP_HOME/
WORKDIR $APP_HOME
ENTRYPOINT ["sh", "-c"]
CMD ["exec java -jar $APP_FILE"]
