# Mission 4: The Cloud-Native Engineer

## Mission Overview
This laboratory activity introduces the fundamentals of cloud-native engineering by examining the differences between traditional Virtual Machines (VMs) and containers. Using the KillerCoda Docker environment, the activity covers basic Docker commands and the deployment of an Nginx web server inside a container. It also demonstrates the container lifecycle through the processes of listing, stopping, and removing a container. The activity provides an understanding of how containerization enables lightweight, portable, and efficient application deployment.

## Objectives
* Differentiate between traditional Virtual Machines (VMs) and Containers.
* Access a Docker-enabled cloud environment using KillerCoda.
* Execute fundamental Docker CLI (Command Line Interface) commands.
* Pull, run, manage, and terminate a containerized application (Nginx).
* Create professional technical documentation of container operations using Markdown.
* Continue developing a well-organized GitHub Cloud Computing Portfolio

## Docker Command Executed
1. `docker --version`
→ This command checks the installed Docker version and confirms that Docker is available in the environment.
2. `docker info`
→ This command displays information about the Docker installation and its current environment.
3. `docker pull nginx`
→ This command downloads the official Nginx image from Docker Hub.
4. `docker run -d -p 8080:80 --name nginx-server nginx`
→ This command creates and starts an Nginx container in detached mode and maps host port 8080 to container port 80.
5. `curl http://localhost:8080`
→ This command sends an HTTP request to the Nginx server and verifies that the web server is responding.
6. `docker ps`
→ This command lists the currently running Docker containers.
7. `docker stop nginx-server`
→ This command stops the running Nginx container.
8. `docker ps`
→  This command verifies whether the Nginx container is no longer running.
9. `docker rm nginx-server`
→ This command permanently removes the stopped Nginx container.

## Skills Learned
This activity taught the basic Docker commands used to run and manage containers. It also helped explain how to pull an image, run an Nginx container, and use port mapping between the host and container. The activity also showed how to check if a container is running and how to stop and remove it. Basic Markdown documentation and file organization were also practiced.

## Challenges Encountered
Some challenges were understanding the difference between a Docker image and a container. Understanding port mapping, especially the connection between ports 8080 and 80, was also a challenge. Remembering the correct Docker commands and following them in the right order took some practice. Checking the terminal output after each command helped in understanding what was happening.
