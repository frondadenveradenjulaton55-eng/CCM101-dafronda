# Mission 6 Reflection

## Reflection

The use of Docker Compose made the deployment easier to organize because the configurations for the application services were written in a single YAML file. Instead of treating the Nextcloud and MariaDB containers as completely separate tasks, their settings could be defined together and managed as one application. This demonstrates how Infrastructure as Code can simplify repeated deployment tasks.

Another lesson from this activity was the importance of correct YAML indentation. YAML uses spaces to represent the structure of the configuration, so the placement of each line matters. If a Tab is used incorrectly or the indentation does not follow the expected structure, Docker Compose may produce an error when reading the file.

The environment variables provide the containers with information needed for their operation. For example, `MYSQL_DATABASE`, `MYSQL_USER`, and `MYSQL_PASSWORD` define important database settings. The `MYSQL_HOST` variable is especially important for the connection because it tells Nextcloud that the database can be reached through the service named `database`.

Accessing the Nextcloud page through the browser helped me understand the connection between the configuration and the final result. After the containers were started, the application could be reached through the assigned port, showing how containerized services can provide a working cloud application.

My understanding of Cloud Computing has progressed since Mission 1. I now have a clearer understanding of how containers, application services, databases, networking, and configuration files can be combined. This mission also showed me how deployment can be made more consistent through automation and Infrastructure as Code.
