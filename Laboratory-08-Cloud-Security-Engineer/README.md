## Mission Overview

This laboratory focuses on improving Linux server security through firewall configuration and network access control. The activity includes running an Nginx web server in Docker, configuring UFW rules, and checking the server's accessibility.

## Objectives

- Understand the importance of firewall protection.
- Apply the Principle of Least Privilege.
- Configure UFW to control incoming and outgoing traffic.
- Allow required services and ports.
- Verify firewall settings and web server accessibility.
- Document the security configuration and test results.

## Commands Executed

- `docker --version` – checks the installed Docker version.
- `docker run` – starts an Nginx container.
- `docker ps` – displays running containers.
- `curl` – tests HTTP connectivity.
- `sudo ufw allow ssh` – allows SSH traffic.
- `sudo ufw default deny incoming` – sets incoming traffic to be denied by default.
- `sudo ufw default allow outgoing` – allows outgoing traffic by default.
- `sudo ufw enable` – enables the firewall.
- `sudo ufw status verbose` – displays detailed firewall information.
- `sudo ufw allow 8080/tcp` – allows TCP traffic on port 8080.
- `sudo ufw status numbered` – lists firewall rules with numbers.

## Skills Learned

- Basic Linux server security.
- Docker container management.
- Firewall configuration using UFW.
- Network connectivity testing.
- Applying access control principles.
- Writing technical documentation in Markdown.
