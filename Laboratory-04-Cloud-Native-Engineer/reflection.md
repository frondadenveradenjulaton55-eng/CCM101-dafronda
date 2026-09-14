# Mission Reflection

## Reflection

In this laboratory activity, I learned how Docker containers can be used to deploy applications more easily. I compared containers with Virtual Machines and understood that a VM requires a complete operating system, while a container shares the host operating system. Because of this difference, containers are generally lighter and can start faster. This helped me understand why containers are useful for web applications and cloud environments.

One thing I learned was the difference between starting a Docker container and setting up a Virtual Machine. Installing and configuring a VM requires more resources because the operating system also needs to be installed and started. With Docker, I was able to pull the Nginx image and run it as a container using only a few commands. This showed me that containers can be a faster and simpler way to deploy an application.

The port mapping `-p 8080:80` was also important when I deployed Nginx. Port 8080 is the port used on the host, while port 80 is the port used by Nginx inside the container. The mapping allowed me to access the Nginx web server through `http://localhost:8080`. Using the `curl` command helped me check if the web server was responding correctly.

I also learned what happens when a container is removed using `docker rm`. The container is deleted from Docker, including data that was stored only in its writable container layer. If important data needs to remain after the container is removed, persistent storage such as Docker volumes should be used.

Containerization can also improve teamwork between developers and IT operations. Developers can package an application and its required environment into a container, while the IT team can run the same container without repeating the entire setup. This can make development, testing, and deployment more consistent and supports the DevOps approach.

Finally, this activity helped improve my GitHub portfolio. I added my VM and container comparison, Docker commands, deployment documentation, screenshots, and reflection. It shows the progress I am making in cloud computing and gives me practical experience using Docker and containerization.

