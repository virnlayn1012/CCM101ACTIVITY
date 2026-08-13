# Cloud Infrastructure Investigation

## Introduction

The Linux server provided through the KillerCoda Ubuntu playground was inspected using several Linux command-line utilities. The investigation focused on identifying the operating system, kernel, processor, memory, disk, mounted filesystems, hostname, and network addresses.

## Operating System

The server is running Ubuntu 24.04.4 LTS, also known as Noble Numbat.

The operating system information reported:

- Name: Ubuntu
- Version: 24.04.4 LTS
- Version ID: 24.04
- Codename: noble

## Kernel

The Linux kernel version is:

`6.8.0-136-generic`

The kernel is responsible for managing system resources and providing communication between the operating system and hardware.

## CPU

The reported CPU model is:

`Intel Xeon E312xx (Sandy Bridge, IBRS update)`

The environment provides **1 CPU core**.

## Memory

The server has approximately **1.9 GiB of RAM**.

At the time of the investigation, approximately 411 MiB was being used and around 1.5 GiB was available.

## Disk

The server has a **20 GB virtual disk** named `/dev/vda`.

The main root partition is `/dev/vda1`, with approximately 19 GB of capacity.

## Mounted File Systems

| Filesystem | Type | Size | Used | Available | Mount Point |
|---|---|---:|---:|---:|---|
| tmpfs | tmpfs | 191M | 1000K | 190M | `/run` |
| /dev/vda1 | ext4 | 19G | 5.4G | 13G | `/` |
| tmpfs | tmpfs | 952M | 84K | 952M | `/dev/shm` |
| tmpfs | tmpfs | 5.0M | 0 | 5.0M | `/run/lock` |
| /dev/vda16 | ext4 | 881M | 117M | 703M | `/boot` |
| /dev/vda15 | vfat | 105M | 6.2M | 99M | `/boot/efi` |

## Hostname

The hostname reported by the server is:

`ubuntu`

## IP Address

The server reported these addresses:

- `172.30.1.2`
- `172.17.0.1`

The primary address used for the investigation is `172.30.1.2`.

## Conclusion

The investigation showed that the KillerCoda environment provides a small virtual Linux server with one CPU core, 1.9 GiB of RAM, and a 20 GB virtual disk. These resources demonstrate the basic compute, storage, operating system, and networking components found in a cloud environment.
