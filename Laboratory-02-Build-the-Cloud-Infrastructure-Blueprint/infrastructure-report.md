# Cloud Infrastructure Assessment Report

## 1. Server Information

| Item | Details |
|---|---|
| **Operating System** | Ubuntu 24.04.4 LTS |
| **Kernel Version** | 6.8.0-136-generic |
| **CPU Model** | Intel Xeon E312xx (Sandy Bridge, IBRS update) |
| **CPU Cores** | 1 |
| **Total RAM** | 1.9 GiB |
| **Disk Capacity** | 19 GB |
| **Hostname** | ubuntu |
| **IP Address** | 172.30.1.2 / 172.17.0.1 |

## 2. Operating System

The server is running **Ubuntu 24.04.4 LTS**. Ubuntu is the Linux operating system used to manage the server and run its applications and services.

## 3. Kernel Version

The server is using kernel version:

`6.8.0-136-generic`

The kernel is responsible for managing the system's hardware and allowing software to communicate with the hardware.

## 4. CPU

**CPU Model:** Intel Xeon E312xx (Sandy Bridge, IBRS update)

**Number of CPU Cores:** 1

The CPU provides the processing power needed to execute commands and run applications on the server.

## 5. Memory

**Total RAM:** 1.9 GiB

The available memory is used by the operating system and running processes on the server.

## 6. Disk Capacity

The main disk has a total capacity of **19 GB**.

| File System | Size | Used | Available | Mounted On |
|---|---:|---:|---:|---|
| `/dev/vda1` | 19 GB | 5.4 GB | 13 GB | `/` |

The main disk uses the **ext4** file system.

## 7. Mounted File Systems

The investigation showed several mounted file systems:

| Mount Point | File System |
|---|---|
| `/` | ext4 |
| `/sys` | sysfs |
| `/proc` | proc |
| `/dev` | devtmpfs |
| `/run` | tmpfs |
| `/boot` | ext4 |
| `/boot/efi` | vfat |

These file systems are used by Linux for storing data and managing different parts of the operating system.

## 8. Hostname

**Hostname:** `ubuntu`

The hostname identifies the Linux server within its environment.

## 9. IP Address

The terminal showed the following IP addresses:

- `172.30.1.2`
- `172.17.0.1`

The main IP address used for this report is **172.30.1.2**.

## 10. Investigation Summary

The investigation of the KillerCoda cloud server revealed the following information: It is running th Ubuntu 24.04.4 LTS operating system, and the kernel is 6.8.0-136-generic. This server is equipped with 1 CPU core and an Intel Xeon E312xx (Sandy Bridge, IBRS update) processor. It also has a total of 1.9 GiB of RAM that is used by the operating system and active processes.

The main disk is **/dev/vda1** with a total capacity of 19 GB to be used for storage. Use of approximately 5.4 GB was found and remained unused 13 GB. Mounted at `/` is the main file system called **ext4**. For other mounted file systems, such as /sys, /proc, /dev, /run, /boot, and /boot/efi, there were observations.

The name of the server machine is ubuntu. The terminal returned two IP addresses, **172.30.1.2** and **172.17.0.1**, with **172.30.1.2** used as the main IP address for this report. These results are intended to give a general overview of the compute, memory, storage, operating system and networking resources of the KillerCoda environment.

Overall the investigation helped identify the basic infrastructure resource of the Linux server prior to deployment of cloud services or applications.
