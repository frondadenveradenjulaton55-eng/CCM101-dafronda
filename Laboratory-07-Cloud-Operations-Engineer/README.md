# Mission Overview

This laboratory activity focuses on cloud operations and monitoring. The task involves checking the Linux server's resources, deploying an Nginx web server in a Docker container, generating web traffic, checking application logs, and monitoring the container's performance.

# Objectives

- Utilize native Linux command-line tools to monitor host CPU, Memory, and Disk capacity.
- Deploy a web container and track its real-time performance using Docker metrics.
- Generate web traffic and extract application access logs for analysis.
- Translate raw performance data into a readable technical report using Markdown.
- Continue expanding a professional GitHub Cloud Computing Portfolio.

# Monitoring Commands Executed

```bash
free -h
```

```bash
df -h /
```

```bash
top
```

```bash
docker run -d -p 8080:80 --name client-website nginx
```

```bash
curl http://localhost:8080
```

```bash
curl http://localhost:8080/hidden-admin-page
```

```bash
docker logs client-website
```

```bash
docker stats
```

# Skills Learned

- Linux server monitoring
- Memory and disk monitoring
- CPU and process monitoring
- Docker container deployment
- HTTP request testing
- Application log analysis
- Container performance monitoring
- Markdown technical documentation
