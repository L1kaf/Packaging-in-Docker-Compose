### Hexlet tests and linter status:
[![Actions Status](https://github.com/L1kaf/devops-for-programmers-project-74/actions/workflows/hexlet-check.yml/badge.svg)](https://github.com/L1kaf/devops-for-programmers-project-74/actions)
![Docker hub push](https://github.com/L1kaf/devops-for-programmers-project-74/actions/workflows/push.yml/badge.svg)

### Description:
---
This repository packages the js-fastify-blog application into a Docker image. The application already uses the 12 factor methodology, this minimizes the differences between the development and production environments.

Docker Compose is used to set up an environment for development, running tests and CI. After successful CI execution, the application image is collected and published to hub.docker.com. This will make setting up and running the application a matter of minutes, without instructions.

Dockerhub image: likaf/devops-for-programmers-project-74

### System Requirements:
---
* Linux
* Docker

### Usage:
---
```bash
make ci
make env
make start
```
Open in browser: http://0.0.0.0:8080

