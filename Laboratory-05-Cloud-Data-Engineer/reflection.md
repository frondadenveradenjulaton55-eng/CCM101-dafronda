# Mission 5 Reflection

This laboratory helped me understand why object storage is useful for applications that need to store a large number of photos. Object storage is better suited for millions of photos because it is designed to store large amounts of unstructured data as individual objects. Each object can contain the file and related metadata, making it practical for applications where users continuously upload images.

Docker made the deployment of MinIO easier because I did not have to manually install and configure all the components of the storage server. By using a Docker command, I was able to download the MinIO image, create a container, configure the administrator credentials, and map the required ports. This showed me how containerization can simplify the deployment of cloud services.

A bucket is a container used to organize objects in an object storage system. In this activity, I created a bucket named `client-photos` and uploaded a test file into it. The successful upload showed that the MinIO storage server was working properly.

Large enterprise companies can protect their object storage data from physical server failures by using redundancy, replication, backups, and multiple storage locations. By keeping additional copies of important data, companies can recover information when a storage device or physical server fails.

My confidence in navigating the Linux command line is gradually improving. At first, I needed to carefully follow the Docker commands because small syntax errors could prevent the container from starting. After using commands such as `docker pull`, `docker run`, and `docker ps`, I became more comfortable working in the terminal. I learned how Docker commands can be used to deploy and check cloud services. I still need more practice, but this laboratory helped me become more confident with Linux and Docker.

