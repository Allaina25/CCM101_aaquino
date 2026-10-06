# Checkpoint 7 - Mission Reflection

Writing a `docker-compose.yml` file makes a cloud engineer's job easier because the configuration for the application can be placed in one file. Instead of manually typing many `docker run` commands, we can simply use Docker Compose to create and start the required containers. This also makes the deployment easier to repeat because the same configuration can be used again on another computer or server.

If I make an indentation error in a YAML file, the file may not work correctly. YAML depends on proper indentation to understand the structure of the configuration. For example, using a Tab instead of spaces can cause a YAML parsing error. Docker Compose may stop and show an error instead of starting the containers. This taught me that even small formatting mistakes can affect the whole deployment.

We used environment variables such as `MYSQL_PASSWORD` because they allow us to provide important configuration values to the containers without placing the settings directly into the application commands. They also make the Compose file easier to configure and change. In a real cloud environment, sensitive information should be handled more securely using secrets or other secure methods.

Deploying a fully functional cloud storage system like Nextcloud in only a few minutes felt convenient and impressive. I realized that Docker can make the deployment of complex applications much faster because the required services can be configured and started together.

Since Mission 1, my understanding of Cloud Computing has improved. Before, I mainly thought of cloud computing as storing files and accessing applications through the internet. Now, I understand that cloud computing also involves containers, servers, networking, databases, automation, and deployment. This mission helped me see how these technologies work together to create a working cloud application.
