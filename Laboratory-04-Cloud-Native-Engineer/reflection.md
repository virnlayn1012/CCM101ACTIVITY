# Mission Reflection

Working with Docker containers showed me how fast and simple they are compared to Virtual Machines. A VM needs a full operating system to be installed, which can take many minutes and use a lot of RAM. In contrast, a Docker container can start in just a few seconds because it shares the host system resources and only runs what is needed for the application. This makes containers very lightweight and efficient, which is why they are becoming popular in modern cloud computing.

Port mapping is important when running a web server inside a container. By default, the container is isolated and cannot be reached from outside. Using `-p 8080:80` connects port 8080 on the host machine to port 80 inside the container. This allows me to access the Nginx web server from my browser or curl command using `localhost:8080`. Without port mapping, the service would run but remain hidden from the outside world.

When I use the `docker rm` command, the container is deleted completely. This means all data inside that container is lost unless I saved it in a volume or external storage. It taught me that containers are temporary by design, and I should plan carefully if I need to keep data for long-term use.

Containerization also changes how developers and IT teams work together. In DevOps, developers can package their applications with all dependencies inside a container, and operations teams can deploy them easily without worrying about setup differences. This reduces conflicts and speeds up delivery, making teamwork smoother and more reliable.

Finally, my GitHub portfolio is growing with each lab. It now includes structured folders, Markdown documentation, and screenshots that show my progress. This portfolio is becoming a record of my learning journey and will be useful when I present my skills to future employers or during academic defenses.
