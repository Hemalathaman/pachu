# Use Java 11
FROM openjdk:11-jdk

#COPY JAR FILE
COPY build/libs/app.jar/app.jar
EXPOSE 8010
CMD java -jar /app.jar

ENTRYPOINT ["java","-jar","/yadacode-aws-springboot-dp-1.0.0.jar"]
