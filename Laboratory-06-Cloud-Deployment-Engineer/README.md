# Laboratory 06 - Cloud Deployment Engineer

## Mission Overview

This mission focused on deploying a cloud-based application using Docker and Docker Compose. We created a Compose file that configured the Nextcloud application and its database. The goal was to understand how multiple containers can work together as one cloud application.

## Objectives

* Understand the purpose of Docker Compose.
* Create and use a `docker-compose.yml` file.
* Configure Nextcloud and a database container.
* Use environment variables for application settings.
* Connect the Nextcloud container to the database container.
* Deploy multiple containers using one command.

## Commands Executed

```bash
mkdir nextcloud-deployment
cd nextcloud-deployment
nano docker-compose.yml
docker-compose up -d
docker-compose ps
docker-compose logs
```

We also used Docker commands during the previous missions, including:

```bash
docker run
docker ps
docker images
```

## Skills Learned

During this mission, I learned how to create a Docker Compose configuration and use it to deploy multiple containers. I also learned how containers can communicate with each other using service names and environment variables. Another skill I learned was how to check the status and logs of running containers. Overall, I became more comfortable with using Docker for cloud application deployment.
