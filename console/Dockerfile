FROM java:8
VOLUME /tmp
ADD rocketmq-console-ng.jar app.jar
ENV JAVA_OPTS=""
ENTRYPOINT [ "sh", "-c", "java $JAVA_OPTS -jar /app.jar" ]
