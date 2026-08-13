# Cloud Infrastructure Components

## Compute Resources

Compute resources are responsible for processing tasks and running applications. They include resources such as CPU and memory.

The KillerCoda environment provides an Intel Xeon E312xx processor with one available CPU core and approximately 1.9 GiB of RAM. Although this is a small environment, it is enough to demonstrate how a cloud server uses computing resources.

Compute is important in cloud computing because applications require processing power to operate. Cloud providers allow customers to select computing resources based on their workloads.

## Storage Resources

Storage resources provide a location for operating system files, applications, and data.

The KillerCoda server has a 20 GB virtual disk named `/dev/vda`. Its main partition, `/dev/vda1`, provides approximately 19 GB and uses the ext4 filesystem.

Cloud storage is important because applications need reliable locations for saving and retrieving information.

## Networking Resources

Networking resources allow a server to communicate with users, applications, and other systems.

The KillerCoda environment reported the IP addresses `172.30.1.2` and `172.17.0.1`. The primary address observed during the investigation was `172.30.1.2`.

Networking is essential in cloud computing because cloud resources need to communicate with each other and with users.

## Operating System

The operating system manages the server's hardware and provides the environment where applications and commands operate.

The KillerCoda environment runs Ubuntu 24.04.4 LTS with Linux kernel version `6.8.0-136-generic`.

Linux is commonly used in cloud environments because it provides a flexible server platform and supports many cloud-based applications and services.

## Relationship of the Components

These components work together to form the cloud server. The operating system manages the CPU, memory, storage, and networking resources. The compute resources process tasks, storage keeps information, and networking allows communication with other systems.
