FROM openjdk:8-jre-alpine
ENV APP_FILE flight-eureka-server-0.3.jar
ENV APP_HOME /usr/apps
EXPOSE 7100
COPY target/$APP_FILE $APP_HOME/
WORKDIR $APP_HOME
ENTRYPOINT ["sh", "-c"]
CMD ["exec java -jar $APP_FILE"]