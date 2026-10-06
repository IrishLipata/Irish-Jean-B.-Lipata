# Mission Reflection

Writing a `docker-compose.yml` file makes a cloud engineer's job easier because it allows multiple containers and their configurations to be defined in one file. Instead of manually typing many commands to create and configure each container, Docker Compose can deploy the entire application stack using one command. This makes the deployment process more organized, repeatable, and less prone to errors.

If there is an indentation error in a YAML file, such as using a Tab instead of Spaces, the configuration may not be interpreted correctly. Since YAML depends on proper indentation to understand the structure of the configuration, an indentation mistake can cause Docker Compose to report an error and prevent the application from being deployed.

We used environment variables such as `MYSQL_PASSWORD`, `MYSQL_DATABASE`, and `MYSQL_USER` to provide the database configuration needed by the application. These variables allow the Nextcloud container to know the database credentials and the database it needs to use. The `MYSQL_HOST=database` variable also allows Nextcloud to find the MariaDB container through its service name.

Deploying Nextcloud in just a few minutes made the deployment process feel more efficient and practical. It demonstrated how containers and Docker Compose can simplify the deployment of an enterprise cloud storage system.

Since Mission 1, my understanding of Cloud Computing has evolved from learning basic cloud concepts to understanding how cloud applications can be deployed, connected, and managed using containers. This mission helped me understand Infrastructure as Code and how automation can make cloud deployment more consistent and efficient.
