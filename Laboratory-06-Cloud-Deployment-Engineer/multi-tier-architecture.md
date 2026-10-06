# Checkpoint 2 – Research: Multi-Tier Architecture

## What is a Two-Tier Architecture?

A **Two-Tier Architecture** is a system divided into two main parts: the **Web/Application Tier** and the **Database Tier**. The web/application tier handles the user interface and requests, while the database tier stores and manages the system's data.

### The Web/Application Tier

The Web/Application Tier is responsible for serving the website or application to the user. It handles HTTP requests, processes user actions, and communicates with the database when information is needed.

### The Database Tier

The Database Tier is responsible for storing and managing persistent data. This can include user accounts, passwords, application settings, and other information that needs to be saved.

### Why Separate Them?

It is better to keep the web server and database in separate containers because each container can focus on its own job. This makes the system easier to manage, update, and troubleshoot, and it also provides better security by separating the application from the database.
