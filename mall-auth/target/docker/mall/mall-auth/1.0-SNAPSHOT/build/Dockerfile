FROM java:8
MAINTAINER macrozheng
COPY maven /
ENTRYPOINT ["java", "-jar","-Dspring.profiles.active=prod","/mall-auth-1.0-SNAPSHOT.jar"]
