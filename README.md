# Jenkins Docker image with Chrome and Java

[![Docker Stars](https://img.shields.io/docker/stars/jenkins/jenkins.svg)](https://hub.docker.com/r/jenkins/jenkins/)
[![Docker Pulls](https://img.shields.io/docker/pulls/jenkins/jenkins.svg)](https://hub.docker.com/r/jenkins/jenkins/)
[![Join the chat at https://gitter.im/jenkinsci/docker](https://badges.gitter.im/jenkinsci/docker.svg)](https://gitter.im/jenkinsci/docker?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

<img src="https://jenkins.io/sites/default/files/jenkins_logo.png"/>

# Usage

## Default image

```shell
docker run -p 8080:8080 -p 50000:50000 \
--restart=on-failure \
mayraamaral/jenkins-docker-chrome-java:latest
```

## Image with Nodejs installed

```shell
docker run -p 8080:8080 -p 50000:50000 \
--restart=on-failure \
mayraamaral/jenkins-docker-chrome-java:node
```

NOTE: this is only a fork, the original repository is from [official jenkins](https://github.com/jenkinsci/docker)

# Image repo

Link: https://hub.docker.com/r/mayraamaral/jenkins-docker-chrome-java
