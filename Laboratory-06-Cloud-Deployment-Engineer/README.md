# Laboratory 06 - Cloud Deployment Engineer

## Mission Overview

This laboratory activity demonstrates the deployment of a private cloud storage application using Docker Compose. The system is composed of a Nextcloud application service and a MariaDB database service that work together as a multi-tier application.

## Objectives

* Explain how a two-tier architecture works.
* Identify the purpose of the services in a Docker Compose file.
* Create a YAML configuration using the Linux `nano` editor.
* Deploy and manage multiple containers with Docker Compose.
* Apply Infrastructure as Code concepts in a containerized environment.
* Record the activity and its results using Markdown.

## Commands Executed

```bash
mkdir nextcloud-deployment
cd nextcloud-deployment
nano docker-compose.yml
docker-compose up -d
docker-compose ps
docker-compose down
```

## Skills Learned

I learned how to work with Docker Compose, YAML configuration files, Linux terminal commands, container networking, environment variables, multi-container applications, and Markdown documentation.
