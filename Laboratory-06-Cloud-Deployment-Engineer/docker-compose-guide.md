# Docker Compose Guide

## What Does the `services:` Block Do?

The `services:` block contains the definitions of the components that make up the application. In the configuration used for this activity, the `database` service provides MariaDB and the `app` service provides Nextcloud.

## How Did the Nextcloud App Container Find the Database?

The database connection information is provided to the Nextcloud container through environment variables. The setting `MYSQL_HOST=database` specifies the service name that Nextcloud should use when connecting to MariaDB. Since `database` is the name of the MariaDB service, Docker Compose can use it to establish communication between the containers.

## What is the Difference Between `docker run` and `docker-compose up -d`?

`docker run` is a Docker command that can create and start a container using options supplied directly in the command. `docker-compose up -d` instead uses the configuration in the `docker-compose.yml` file to start the services defined for the application. Using Docker Compose is useful when several containers need to be deployed as one application, and `-d` keeps them running in the background.
