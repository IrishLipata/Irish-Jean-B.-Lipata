# Two-Tier Architecture

## The Web/Application Tier

The Web/Application Tier is responsible for providing the user interface and handling HTTP requests from users. In this activity, the Nextcloud application serves as the web application that users access through a web browser.

## The Database Tier

The Database Tier is responsible for storing persistent data required by the application. In this activity, MariaDB stores information such as user accounts and other data needed by Nextcloud.

## Why Separate Them?

Separating the web/application server and database into two containers makes the system easier to manage and maintain. Each container has a specific responsibility, allowing the application and database to operate independently while communicating with each other when needed.

