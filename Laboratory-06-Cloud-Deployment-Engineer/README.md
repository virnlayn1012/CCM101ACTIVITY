# Mission 6: Cloud Development Engineer

## Mission Overview
In this laboratory activity, I learned how to deploy a multi-container application using Docker Compose. Unlike previous missions that focused on deploying single containers, this mission introduced a two-tier architecture consisting of a Nextcloud web application and a MariaDB database. Using Infrastructure as Code (IaC) principles, I created a `docker-compose.yml` file to define and deploy both containers with a single command. This approach simplifies deployment, reduces configuration errors, and improves consistency across environments.

## Objectives
- Explain the concept of a multi-tier application architecture.
- Understand the purpose and structure of a `docker-compose.yml` file.
- Create and edit configuration files using the Linux text editor `nano`.
- Deploy a multi-container application using Docker Compose.
- Connect a Nextcloud container to a MariaDB database container.
- Document deployment procedures and Infrastructure as Code (IaC) concepts using Markdown.
- Continue building a professional GitHub Cloud Computing Portfolio.

## Command Executed
The following commands were used during the deployment process:
 
### Create the Project Directory
```bash
mkdir nextcloud-deployment
cd nextcloud-deployment
```
### Create the Docker Compose Configuration File
```bash
nano docker-compose.yml
```
### Deploy the Nextcloud and MariaDB Containers
```bash
docker-compose up -d
```
### Verify Running Services
```bash
docker-compose ps
```
### Stop and Remove the Deployment
```bash
docker-compose down
```

## Skills Learned
- Understanding multi-tier application architecture.
- Writing and managing Docker Compose YAML files.
- Using Infrastructure as Code (IaC) for deployments.
- Deploying Nextcloud and MariaDB containers simultaneously.
- Configuring container communication through Docker networking.
- Using environment variables for application configuration.
- Managing multi-container applications with Docker Compose.
- Creating technical documentation using Markdown.
- Using Git and GitHub for version control and portfolio development.
