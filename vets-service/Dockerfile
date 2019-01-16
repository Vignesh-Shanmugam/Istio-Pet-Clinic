FROM openjdk:8-jre-alpine
ENV APP_FILE spring-petclinic-vets-service-2.0.6.jar
ENV APP_HOME /usr/app
EXPOSE 7998
COPY target/$APP_FILE $APP_HOME/
WORKDIR $APP_HOME
ENTRYPOINT ["sh", "-c"]
CMD ["exec java -jar $APP_FILE"]