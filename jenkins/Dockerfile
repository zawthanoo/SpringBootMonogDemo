FROM openjdk:8-jdk-alpine
RUN mkdir -p /usr/local/myapp/config
COPY /apps/*.jar /usr/local/myapp/
#ENTRYPOINT [ "sh", "-c", "java -Xms${MAX_JVM_MEMORY}m -Xmx${MIN_JVM_MEMORY}m -XX:NewRatio=${JVM_MEMORY_NEW_RATIO} -Dspring.config.location=classpath:application.yaml,file:///usr/local/myapp/config/application-override.yaml, -jar /usr/local/myapp/SpringBootMonogDemo.jar" ]
