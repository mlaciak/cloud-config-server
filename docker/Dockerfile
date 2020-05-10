FROM openjdk:11-jre
EXPOSE 8888
RUN mkdir /app
COPY * /app/
WORKDIR /app/
ARG GITURI=https://github.com/mlaciak/Cloudrepo
ARG GITUSER=testutestu
ARG GITPASS=workuworku1
ENV GIT_SCCS=$GITURI
ENV GIT_USERN=$GITUSER
ENV GIT_PASSWD=$GITPASS
ENTRYPOINT java -jar /app/app.jar