FROM goodforgod/debian-jre10server-oracle

COPY helloworld-1.0.0.jar /
VOLUME /tmp/logs

USER app

# Just execute 'run.sh' to build and run container
# Then go to 'http://localhost:8080'

ENTRYPOINT ["java", "-jar", "/helloworld-1.0.0.jar"]