# Mission 3 : Multi-Cloud Explorer

## Mission Overview

This laboratory activity explores and compares three major cloud platforms: Amazon Web Services (AWS), Microsoft Azure, and Google Cloud Platform (GCP).

The mission focuses on identifying cloud services, comparing their capabilities, analyzing business requirements, and recommending suitable cloud platforms for different scenarios.

## Cloud Platforms

* Amazon Web Services (AWS)
* Microsoft Azure
* Google Cloud Platform (GCP)

## Objectives

* Explore major public cloud platforms.
* Identify core cloud services.
* Compare AWS, Azure, and GCP.
* Recommend suitable cloud platforms for different business needs.
* Use Linux commands to examine a server environment.
* Document the laboratory activities using Markdown.

## Linux Server Investigation
## Checkpoint 7

* Operating System
* CPU Information
* Memory
* Disk Space

## Linux Commands
* cat /etc/os-release
* lscpu
* free -h
* df -h

## Operating System
By running the command uname -a, I found that the operating system is Linux Ubuntu 6.8.0-138-generic x86_64 GNU/Linux, which shows the kernel version and architecture.

## CPU Information
Using the command lscpu, I discovered that the CPU is an Intel Xeon E312xx (Sandy Bridge, IBRS update) running at 2.0GHz. It has 1 core with 1 thread per core, and the environment is virtualized under the KVM hypervisor.

## Memory
With the command free -h, I observed that the system has a total of 1.9 GiB of memory, of which 415 MiB is used and 867 MiB is free. The available memory is 1.5 GiB, and there is 1.0 GiB of swap space.

## Disk Space
By executing df -h, I found that the main filesystem /dev/vda1 has a total size of 19G, with 5.4G used and 13G available. Other partitions include /boot with 881M total size and /boot/efi with 105M total size. The root directory (/) is mounted on /dev/vda1.

<img width="1318" height="845" alt="Screenshot 2026-09-01 193942" src="https://github.com/user-attachments/assets/2a46fd46-92e6-44be-a81a-54ebc8709a08" />

<img width="1331" height="666" alt="Screenshot 2026-09-01 194024" src="https://github.com/user-attachments/assets/bddacd69-92a7-4b75-a3d0-ad1aefe1f4a4" />

If the Linux server were migrated to the cloud, the following services could host it:

|Cloud Platform| Service|
|---|---|
|AWS| Amazon EC2|
|Azure| Azure Virtual Machines|
|GCP| Google Compute Engine|

