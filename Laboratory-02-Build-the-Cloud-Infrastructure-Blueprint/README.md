# Laboratory 02 – Build the Cloud Infrastructure Blueprint

## Mission Overview

Congratulations! My onboarding has been successfully completed, and my Cloud Computing Portfolio has been approved by my supervisor.

CloudNova Technologies has assigned me to my first official project. Before any cloud services are deployed, I need to understand the infrastructure that supports modern cloud computing. My mission is to examine the available infrastructure resources and understand how compute, storage, networking, and identity services work together.

Using the KillerCoda Playground, Linux command-line tools, official cloud documentation, and my GitHub Cloud Computing Portfolio, I investigated a cloud-based Linux environment and documented the results as part of the planning process for a possible cloud deployment.

This mission allowed me to connect the concepts discussed in class with an actual Linux environment while developing the technical documentation and problem-solving skills expected of a cloud engineer.

## Mission Objectives

At the end of this laboratory activity, I was able to:

* Explain the major components of cloud infrastructure.
* Investigate hardware and software resources available in a Linux environment.
* Differentiate compute, storage, networking, and identity resources.
* Interpret how different cloud infrastructure components work together.
* Create organized and professional technical documentation using Markdown.
* Continue developing a structured Cloud Computing Portfolio using GitHub.

## Cloud Infrastructure Assessment

| Infrastructure Component | Findings |
|---|---|
| **Operating System** | Ubuntu 24.04.4 LTS (Noble Numbat) |
| **Kernel** | Linux `6.8.0-138-generic` |
| **CPU** | Intel Xeon E312xx (Sandy Bridge, IBRS update) |
| **CPU Cores** | 1 CPU and 1 core |
| **Architecture** | x86_64 |
| **RAM** | 1.9 GiB total |
| **Swap** | 1.0 GiB total |
| **Disk** | 20G virtual disk |
| **Root Partition** | 19G mounted on `/` |
| **Hostname** | `ubuntu` |
| **Primary IP Address** | `172.30.1.2/24` |
| **Docker IP Address** | `172.17.0.1/16` |
| **Default Gateway** | `172.30.1.1` |
| **Hypervisor** | KVM |
| **Virtualization** | Full virtualization |

## Tools Used

| Tool | Purpose |
|---|---|
| **KillerCoda Playground** | Provided the Linux server environment for the investigation |
| **Linux Terminal** | Used to execute commands and collect system information |
| **GitHub** | Used to organize and maintain the Cloud Computing Portfolio |
| **Markdown** | Used to create structured technical documentation |
| **Web Browser** | Used to access KillerCoda, GitHub, and cloud documentation |
| **Draw.io (diagrams.net)** | Used to create the cloud infrastructure diagram |

## Linux Commands Executed

| Command | Purpose |
|---|---|
| `cat /etc/os-release` | Identify the operating system and version |
| `uname -r` | Identify the Linux kernel version |
| `lscpu` | Investigate CPU architecture, model, cores, and virtualization |
| `nproc` | Determine the number of available CPU cores |
| `free -h` | Check RAM and swap memory |
| `df -h` | Check filesystem capacity and usage |
| `lsblk` | Identify disks and partitions |
| `hostname` | Identify the server hostname |
| `ip addr` | Identify network interfaces and IP addresses |
| `ip route` | Identify network routes and the default gateway |
| `mount \| column -t` | Examine mounted filesystems |

## Cloud Infrastructure Components

### Compute Resources

The Linux environment uses an Intel Xeon E312xx processor with one available CPU core. The system uses the x86_64 architecture and runs under the KVM hypervisor with full virtualization.

### Storage Resources

The system contains a 20G virtual disk named `/dev/vda`. The main partition `/dev/vda1` provides 19G of storage and is mounted at `/`.

### Networking Resources

The primary network interface is `enp1s0`, which uses the IPv4 address `172.30.1.2/24`. The system also has a Docker network interface using `172.17.0.1/16`. The default gateway is `172.30.1.1`.

### Operating System

The server runs Ubuntu 24.04.4 LTS with Linux kernel version `6.8.0-138-generic`.

### Identity and Access Management

Identity and access management controls access to cloud resources by determining which users and services can access resources and what actions they are permitted to perform.

The KillerCoda investigation did not provide specific cloud IAM users, roles, or permissions, so no specific IAM configuration is claimed in this report.

## Skills Learned

I learned how to investigate a Linux server using command-line tools and interpret system information. I identified the operating system, kernel, CPU, memory, storage, filesystems, hostname, network interfaces, IP addresses, and routing information.

I also improved my ability to organize technical information using Markdown tables, headings, lists, and code formatting. The activity helped me understand how compute, storage, networking, virtualization, and operating-system resources contribute to a cloud environment.

In addition, I practiced maintaining my Cloud Computing Portfolio through GitHub and learned the importance of documenting technical findings before planning a cloud deployment.

## Challenges Encountered

| Challenge | How I Addressed It |
|---|---|
| **Understanding CPU information** | I reviewed the `lscpu` output to identify the CPU model, architecture, CPU count, cores, and virtualization information. |
| **Interpreting memory information** | I used `free -h` to identify total, used, available, and swap memory. |
| **Understanding disk partitions** | I compared `lsblk` and `df -h` to identify the virtual disk, partitions, sizes, and mount points. |
| **Understanding mounted filesystems** | I used `mount \| column -t` to examine the filesystem mount points and filesystem types. |
| **Understanding network configuration** | I compared `ip addr` and `ip route` to identify interfaces, IP addresses, networks, and the default gateway. |
| **Connecting Linux resources to cloud concepts** | I organized the findings into compute, storage, networking, virtualization, and operating-system categories. |
| **Organizing the documentation** | I used Markdown headings, tables, lists, and code formatting to make the technical information clear and organized. |
