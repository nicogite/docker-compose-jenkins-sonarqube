FROM jenkins/jenkins:lts-jdk11

# Install npm
USER root
RUN apt-get update
RUN apt-get install npm -y

# Install Plugins
#COPY --chown=jenkins:jenkins plugins.txt /usr/share/jenkins/ref/plugins.txt
#RUN jenkins-plugin-cli -f /usr/share/jenkins/ref/plugins.txt

#Docker, docker-build-step, and Cloudbees Docker Build and Publish