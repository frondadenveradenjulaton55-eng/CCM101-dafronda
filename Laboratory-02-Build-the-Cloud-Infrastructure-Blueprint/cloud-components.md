# Cloud Infrastructure Components

## Compute Resources

The Linux environment provided by KillerCoda uses an Intel Xeon E312xx (Sandy Bridge, IBRS update) processor. The system has 1 CPU and 1 CPU core, with an x86_64 architecture and 1.9 GiB of RAM.

The purpose of compute resources is to provide the processing power and memory needed to run the operating system, applications, and other workloads.

Compute resources are important in cloud computing because they allow applications and services to process information and perform tasks. Cloud providers allow these resources to be provisioned according to workload requirements.

In the KillerCoda environment, the CPU and RAM provide the computing capacity used to operate the Ubuntu Linux server and execute the commands required for this laboratory.

## Storage Resources

The KillerCoda environment contains a 20G virtual disk, identified as /dev/vda. The main partition, /dev/vda1, has a capacity of 19G and is mounted on /. The root filesystem uses the ext4 filesystem, with approximately 5.4G used and 13G available.

The purpose of storage resources is to provide space for the operating system, applications, configuration files, and other data.

Storage is important in cloud computing because applications and services need a place to store and retrieve data. Cloud environments provide different types of storage depending on whether workloads require persistent disks, files, or other forms of data storage.

In the KillerCoda environment, the virtual disk provides the storage required by Ubuntu and the files and applications running on the Linux server.

## Networking Resources

The KillerCoda Linux environment has a primary network interface called enp1s0 with the IPv4 address 172.30.1.2/24. The system also has a Docker network interface called docker0, using 172.17.0.1/16. The default gateway is 172.30.1.1.

The purpose of networking resources is to allow computers, applications, and services to communicate with each other.

Networking is important in cloud computing because cloud resources need to communicate with users, applications, databases, and other services. Proper networking allows workloads to exchange data and connect to external or internal resources.

In the KillerCoda environment, the enp1s0 interface provides the main network connection for the Linux server, while docker0 provides a network used by Docker. The routing configuration allows the server to communicate through the configured network and default gateway.

## Operating System

The Linux environment provided by KillerCoda is running Ubuntu 24.04.4 LTS (Noble Numbat) with Linux kernel version 6.8.0-138-generic.

The purpose of an operating system is to manage the computer's hardware and software resources and provide an environment where applications and commands can run.

The operating system is important in cloud computing because cloud servers require an operating system to manage compute, memory, storage, networking, and applications. It also provides the command-line and system-management tools needed to administer a server.

In the KillerCoda environment, Ubuntu provides the operating system used to interact with the virtual server. The Linux commands used during this laboratory, such as lscpu, free, df, lsblk, ip addr, and ip route, allow the infrastructure resources to be investigated and managed.
