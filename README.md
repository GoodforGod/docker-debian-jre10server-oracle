# Docker Debian Oracle Server JRE 10
Docker Debian image with *Oracle Server JRE 10.0.2* (239MB)

You must accept the [Oracle Binary Code License Agreement for Java SE](http://www.oracle.com/technetwork/java/javase/terms/license/index.html) to use this image.

## Image
Image contains cleaned [Oracle Server JRE 10.0.2](http://www.oracle.com/technetwork/java/javase/downloads/sjre10-downloads-4417025.html), you can read about JRE difference [here](https://stackoverflow.com/questions/33407297/difference-between-server-jre-and-client-jre). 
JRE is provided without *desktop, sources* and other unnecessary stuff except JVM. 
So image have all *JVM* parts to run *Java applications* in Docker containers.

Image contains only Java Runtime Environment, so you must have compiled Java application.

Image Tags:

#### *latest* or *stretch*
* Uses base image [Debian Stretch Slim](https://hub.docker.com/_/debian/) *(55.3MB)*
* Image size with Server JRE *(239MB)*

#### *sid*
* Uses base image [Debian Sid Slim](https://hub.docker.com/_/debian/) *(63.3MB)*
* Image size with Server JRE *(254MB)*

## Usage
Image have docker *USER* named **app** so you can use it for your application.

Just add code below in your *Dockerfile* to use start your application as a user *app*
```
USER app
```

Check [example](https://github.com/GoodforGod/https://github.com/GoodforGod/docker-debian-jre10server-oracle/tree/master/example) folder for *Dockerfile* example of image usage.
