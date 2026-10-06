# Laboratory 06 - Cloud Deployment Engineer

## Mission Overview

This mission focuses on deploying a multi-tier private cloud storage application using Docker Compose. The application consists of a Nextcloud web application container and a MariaDB database container that work together as a two-tier architecture.

## Objectives

- Explain the concept of a multi-tier application architecture.
- Understand the purpose and structure of a docker-compose.yml file.
- Use the Linux command-line text editor Nano to create configuration files.
- Deploy a multi-container application using Docker Compose.
- Document deployment procedures and Infrastructure as Code (IaC) principles using Markdown.

## Commands Executed

```bash
mkdir nextcloud-deployment
cd nextcloud-deployment
nano docker-compose.yml
cat docker-compose.yml
docker-compose up -d
docker-compose ps
docker-compose down
