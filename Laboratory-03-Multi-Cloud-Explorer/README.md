
## Checkpoint 7 – Linux Investigation Using KillerCoda

A Linux environment was examined using KillerCoda to gather basic system information. The investigation covered the operating system, CPU, memory, and disk space using standard Linux commands.

---

## 1. Operating System

The following command was used to identify the Linux distribution and version:

This command provides details about the installed Linux distribution, including its name and version.

### Evidence 1 – Operating System

![KillerCoda Terminal 1 - Operating System](screenshots/killercoda-terminal1.png)

---

## 2. CPU Information

The following command was used to examine the CPU information of the Linux environment:

This command provides details about the system processor, such as its architecture, CPU count, and other processor specifications.

### Evidence 2 – CPU Information

![KillerCoda Terminal 2 - CPU Information](screenshots/killercoda-terminal2.png)

---

## 3. Memory
The following command was used to examine the system's memory:


This command shows the total, used, free, and available memory in an easy-to-read format.

### Evidence 3 – Memory

![KillerCoda Terminal 3 - Memory](screenshots/killercoda-terminal3.png)

---

## 4. Disk Space

The following command was used to examine the disk space of the Linux environment:

This command shows the total disk capacity, used space, available space, and percentage of disk usage for mounted file systems.

### Evidence 4 – Disk Space

![KillerCoda Terminal 4 - Disk Space](screenshots/killercoda-terminal4.png)

---

## Linux System Information Summary

| System Information | Command Used | Result |
|---|---|---|
| Operating System | `cat /etc/os-release` |Evidence 1 |
| CPU Information | `lscpu` |Evidence 2 |
| Memory | `free -h` | Evidence 3 |
| Disk Space | `df -h` | Evidence 4 |

---

## Cloud Migration

If this Linux server were migrated to a cloud environment, it could be hosted using virtual machine services offered by AWS, Microsoft Azure, or Google Cloud Platform.
| Cloud Provider | Service That Could Host the Linux Server |
|---|---|
| AWS | Amazon EC2 |
| Microsoft Azure | Azure Virtual Machines |
| Google Cloud Platform (GCP) | Compute Engine |

These cloud services provide virtual computing environments that can be used to run Linux-based workloads.

