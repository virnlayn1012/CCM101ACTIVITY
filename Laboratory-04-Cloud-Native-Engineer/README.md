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
`docker --version` This command checks the installed Docker version and confirms that Docker is available in the environment.
`docker info` : This command displays information about the Docker installation and its current environment.
`docker pull nginx` : This command downloads the official Nginx image from Docker Hub.
`docker run -d -p 8080:80 --name nginx-server nginx` : This command creates and starts an Nginx container in detached mode and maps host port 8080 to container port 80.
`curl http://localhost:8080` : This command sends an HTTP request to the Nginx server and verifies that the web server is responding.
