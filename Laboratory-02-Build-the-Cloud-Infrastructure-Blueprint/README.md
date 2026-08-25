## Mission Overview

Congratulations! My onboarding has been successfully completed, and my Cloud Computing Portfolio has been approved by my supervisor.

CloudNova Technologies has assigned me to my first official project. Before any cloud services are deployed, I need to understand the infrastructure that supports modern cloud computing. My mission is to examine the available infrastructure resources and understand how compute, storage, networking, and identity services work together.

Using the KillerCoda Playground, Linux command-line tools, official cloud documentation, and my GitHub Cloud Computing Portfolio, I investigated a cloud-based Linux environment and documented the results as part of the planning process for a possible cloud deployment.

This mission allowed me to connect the concepts discussed in class with an actual Linux environment while developing the technical documentation and problem-solving skills expected of a cloud engineer.

## Mission Objectives

At the end of this laboratory activity, I was able to:

Explain the major components of cloud infrastructure.
Investigate hardware and software resources available in a Linux environment.
Differentiate compute, storage, networking, and identity resources.
Interpret how different cloud infrastructure components work together.
Create organized and professional technical documentation using Markdown.
Continue developing a structured Cloud Computing Portfolio using GitHub.

Cloud Infrastructure Assessment

The following information was collected from the KillerCoda Linux environment during the investigation:

## Infrastructure Component	Findings
Compute Resources	Intel Xeon E312xx CPU, 1 CPU core, and 1.9 GiB RAM
Storage Resources	Approximately 19G disk capacity with mounted file systems
Networking Resources	IP addresses 172.30.1.2 and 172.17.0.1
Operating System	Ubuntu 24.04.4 LTS

These resources demonstrate the basic infrastructure layers required for a functioning cloud-based server environment.

## Tools Used
Tool	Purpose
KillerCoda Playground	Provided the Linux server environment used for the infrastructure investigation
Linux Terminal	Used to execute commands and collect system information
GitHub	Used to organize, store, and maintain the Cloud Computing Portfolio
Markdown	Used to create structured technical documentation
Web Browser	Used to access KillerCoda, GitHub, and official cloud-provider documentation
Draw.io (diagrams.net)	Used to create the cloud infrastructure architecture diagram

## Linux Commands Executed
Command	Purpose
cat /etc/os-release	Identify the operating system and version
uname -r	Determine the Linux kernel version
lscpu | grep "Model name"	Identify the CPU model
nproc	Determine the number of available CPU cores
free -h	Check available and total memory
df -h	Examine disk capacity and usage
findmnt	Identify mounted file systems
hostname	Determine the server hostname
hostname -I	Display the IP addresses assigned to the system
Cloud Infrastructure Components
Compute Resources

The Intel Xeon E312xx CPU and the available CPU core represent the compute resources of the Linux environment. Compute resources are responsible for processing instructions and running applications and services.

Storage Resources

The Linux environment provides approximately 19G of disk capacity along with mounted file systems. Storage is important because it provides persistent space for the operating system, applications, configuration files, and other data.

Networking Resources

The IP addresses 172.30.1.2 and 172.17.0.1 demonstrate the networking resources available in the environment. Networking allows the server to communicate with other systems and services.

Operating System

The server is running Ubuntu 24.04.4 LTS. The operating system manages system resources and provides the environment required for commands, applications, and services to run.

Identity and Access Management

Identity and access management is responsible for controlling access to cloud resources. It helps determine which users, applications, or services are allowed to access specific resources and what actions they can perform.

## Skills Learned

During this laboratory activity, I learned how to investigate a Linux server using command-line tools and interpret the information returned by those commands. I was able to identify important system resources, including the operating system, kernel, CPU, CPU cores, RAM, disk capacity, mounted file systems, hostname, and IP addresses.

I also improved my ability to organize technical information using Markdown tables, headings, lists, and code formatting. The activity gave me a better understanding of how compute, storage, networking, operating-system, and identity resources contribute to cloud infrastructure.

In addition, I practiced maintaining my Cloud Computing Portfolio through GitHub and learned how technical findings can be documented in a structured and professional way.

## Challenges Encountered
Challenge	How I Addressed It
Understanding the Linux system information	I reviewed the output of each command and identified which values corresponded to the required infrastructure components.
Interpreting mounted file systems	I used the findmnt command and examined the displayed mount points and file-system information.
Identifying network information	I used hostname -I and reviewed the IP addresses assigned to the Linux environment.
Connecting Linux resources to cloud concepts	I categorized the collected information into compute, storage, networking, and operating-system resources.
Organizing the documentation	I used Markdown headings, tables, lists, and code formatting to present the technical information clearly.
