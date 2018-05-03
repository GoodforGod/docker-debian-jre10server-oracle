FROM goodforgod/debian-jre10server-oracle

COPY helloworld-1.0.0.jar /
VOLUME /tmp/logs

USER app

ENTRYPOINT ["java", "-jar", "/helloworld-1.0.0.jar"]