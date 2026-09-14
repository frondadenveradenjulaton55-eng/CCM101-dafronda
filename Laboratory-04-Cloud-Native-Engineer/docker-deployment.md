# Docker Deployment

## Checkpoint 3 - Docker Verification

### Docker Version

```bash
docker --version
```

I used this command to check if Docker was installed and to see the Docker version available in the KillerCoda environment.

### Docker Information

```bash
docker info
```

I used this command to check the Docker environment and verify that Docker was working properly.

## Checkpoint 4 - Nginx Deployment

### Pull Nginx

```bash
docker pull nginx
```

This command downloaded the Nginx image that I needed to create the web server container.

### Run Nginx

```bash
docker run -d --name nginx-server -p 8080:80 nginx
```

This command created and started the Nginx container in the background. The port mapping connected port 8080 of the host to port 80 inside the container.

### Test Nginx

```bash
curl http://localhost:8080
```

I used this command to test the Nginx web server. The command returned the Nginx welcome page, which showed that the web server was running.

## Checkpoint 5 - Container Lifecycle

### List Running Containers

```bash
docker ps
```

This command showed the containers that were currently running.

### Stop the Container

```bash
docker stop nginx-server
```

This command stopped the running Nginx container.

### Check Running Containers

```bash
docker ps
```

I used this command again to verify that the Nginx container was no longer running.

### Remove the Container

```bash
docker rm nginx-server
```

This command removed the stopped Nginx container.

### Check All Containers

```bash
docker ps -a
```

I used this command to check all containers and verify that the Nginx container had been removed.
