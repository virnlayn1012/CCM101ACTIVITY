## What does the services: block do?
 
The `services:` block is the main section of a Docker Compose file where containers are defined. Each service represents a separate container that Docker Compose will create and manage.
 
## How did the Nextcloud app container know how to find the database container?
 
The Nextcloud container connected to the database using the following environment variable:
 
```yaml
MYSQL_HOST: db
```
 
The value `db` matches the name of the database service defined in the Compose file.
Docker Compose automatically creates a shared network for all services. Since both the Nextcloud and MySQL containers are connected to the same network, the Nextcloud application can locate and communicate with the database container using the service name `db` as the hostname.

 
## Difference Between docker run and docker-compose up -d
### docker run
 
- Starts a single container at a time.
- Requires all configuration options to be entered manually.
- Can result in long and complex commands.
- Less efficient when managing multiple containers.
 
Example:
 
```bash
docker run nginx
```
 
### docker-compose up -d
 
- Starts multiple containers from a single configuration file.
- Uses settings stored inside a `docker-compose.yml` file.
- Simplifies deployment and management of multi-container applications.
- Runs containers in detached mode using the `-d` option.
- Makes deployments repeatable and easier to maintain.
 
Example:
 
```bash
docker-compose up -d
```
