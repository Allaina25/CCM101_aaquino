# Checkpoint 6 - Technical Documentation

## What does the `services:` block do?

The `services:` block in the `docker-compose.yml` file defines the containers that will be used by the application. In our project, it contains the Nextcloud application and the database service. Each service has its own settings, such as the Docker image, environment variables, ports, and other configurations. This makes it easier to manage multiple containers as one application.

## How did the Nextcloud app container know how to find the database container?

The Nextcloud app container knows where the database is through the `MYSQL_HOST` environment variable. The value of `MYSQL_HOST` points to the name of the database service in the Compose file. Docker Compose automatically creates a network for the services, so the containers can communicate with each other using their service names. Because of this, Nextcloud can connect to the database without needing to use an IP address.

## Difference Between `docker run` and `docker-compose up -d`

The `docker run` command is normally used to create and start one Docker container at a time. We used it in Mission 4 to manually start a container and provide its settings through the command line.

On the other hand, `docker-compose up -d` is used when we have a Compose file that contains the configuration for multiple services. It can create and start all the required containers using the settings written in the YAML file. The `-d` option means that the containers run in the background.

Using Docker Compose is more convenient because the configuration is saved in one file and can easily be reused.
