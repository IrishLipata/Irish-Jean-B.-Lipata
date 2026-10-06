# Docker Compose Guide

## The Services Block

The `services:` block defines the containers that make up the application. In this project, it contains two services: `database`, which uses the MariaDB image, and `app`, which uses the Nextcloud image.

## How Nextcloud Finds the Database

The Nextcloud app container finds the database container through the `MYSQL_HOST` environment variable. In the Compose file, `MYSQL_HOST=database` tells Nextcloud to connect to the MariaDB container using the service name `database`.

## Docker Run vs Docker Compose Up -d

The `docker run` command is used to create and run an individual Docker container with its required options. In contrast, `docker-compose up -d` uses the Docker Compose configuration file to create and run multiple related containers together in the background. In this activity, Docker Compose deploys both the Nextcloud application and MariaDB database as one multi-container stack.
