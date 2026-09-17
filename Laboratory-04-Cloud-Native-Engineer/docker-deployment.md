# Docker Container Lifecycle (nginx-server)

## Commands and Explanations

1. `docker ps`  
   → Lists all currently running containers; here it showed `nginx-server` running on port 8080.

2. `docker stop nginx-server`  
   → Stops the running container named `nginx-server`.

3. `docker ps`  
   → Confirms that no containers are currently running after stopping `nginx-server`.

4. `docker ps -a`  
   → Lists all containers including stopped ones; shows `nginx-server` in an exited state.

5. `docker rm nginx-server`  
   → Removes the stopped container `nginx-server` from the system.

6. `docker ps -a`  
   → Verifies that the container has been removed and no containers remain.

