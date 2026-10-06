# Mission Reflection

Writing a `docker-compose.yml` file makes a cloud engineer's job much easier because all the container settings are stored in one file. Instead of typing many Docker commands manually, we can define everything once and deploy the entire application with a single command. This saves time, reduces mistakes, and makes the deployment process easier to repeat.

If an indentation error is made in a YAML file, such as using a Tab instead of Spaces, Docker Compose may not be able to read the file correctly. As a result, the deployment can fail and an error message will appear. This is why proper spacing and indentation are very important when writing YAML files.

We used environment variables such as `MYSQL_PASSWORD`, `MYSQL_DATABASE`, and `MYSQL_HOST` to store important configuration settings. Environment variables make the Compose file easier to read and manage. They also allow us to change settings without modifying the application itself.

It felt exciting to deploy a fully functional enterprise cloud storage system like Nextcloud in just a few minutes. Before learning Docker Compose, I thought deploying a cloud application would be a long and difficult process. Seeing both the Nextcloud and database containers work together successfully showed how powerful container technology can be.

My understanding of Cloud Computing has grown a lot. At first, I only thought cloud computing was about storing files and using online services. Now I understand that it also involves deploying applications, managing containers, connecting services, and automating infrastructure. Through this mission, I learned how Infrastructure as Code and Docker Compose help cloud engineers create reliable and organized deployments. Overall, this mission helped me better understand how modern cloud applications are built and managed in real-world environments.
