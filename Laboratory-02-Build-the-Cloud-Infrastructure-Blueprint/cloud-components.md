# Cloud Infrastructure Components

## Introduction

While investigating the KillerCoda Linux server I was able to discover several basic components of an infrastructure used in a cloud environment. They encompass compute, storage, networking as well as operating system. While each one plays a specific part, they all collaborate to run the server and enable apps and services to function.

---

## 1. Compute Resources

### Purpose

Compute resources are the power of a computer or server. The CPU performs the instructions of the operating system and applications. The number of CPU cores will also influence the number of processing tasks the system can process simultaneously.

Cloud Computing is essential for any business.Businesses cannot live without cloud computing.

One of the primary components of cloud infrastructure is compute resources, which is where applications are executed. Cloud computing enables organizations to choose various levels and types of compute resources based on the workload. For instance, the amount of CPU required for a simple application can be small, and for a system that has many users, it may need more CPU.

One other benefit to cloud computing is the ability to scale compute resources up and down based on the needs of the application. This makes it easier for organisations to not need to acquire physical servers with each additional load.

### KillerCoda Environment

The KillerCoda server is running on an Intel Xeon E312xx (Sandy Bridge, IBRS update) processor. This server has 1 CPU core.

The compute resource that is available in the environment is the CPU. It is used when the Linux operating system is running, while terminal commands are executed and as the services run on the server are processed.

---

## 2. Storage Resources

### Purpose

The storage resources are used for storing the operating system, applications, configuration files, and other data. The server would not be able to store the important files and data for system and application use if they were not stored in a permanent location.

It is crucial in cloud computing.

In cloud computing, storage is a crucial factor since applications and services are continually creating and accessing data. Cloud providers provide various storage options for various kinds of data and purpose.

Infrastructure planning needs to take into account storage capacity. If the application generates a significant amount of data, then there needs to be sufficient storage capacity to meet the demands of the application. Another advantage of checking disk usage is that it allows you to avoid issues that can arise from running out of storage space.

### KillerCoda Environment

In the KillerCoda environment the primary storage device is: /dev/vda1. It has a total capacity of **19 GB**. The amount used was 5.4 GB at the time of the investigation and there was around 13 GB available.

This is the main file system, ext4, mounted at /. Other mounts in the mount table that are not related to storage were also seen, such as /boot and /boot/efi.

The disk contains the files and operating system used by Ubuntu and the Linux environment.

---

## 3. Networking Resources

### Purpose

Networking resources enable a server to communicate with other computers, devices and services. One of the fundamental attributes used to uniquely identify a device on a network is an IP address.

Networking can also enable users and applications to use services on a server. A cloud server without network connectivity would not be able to communicate with other resources or accept requests from clients.

### Importance in Cloud Computing

In the world of Cloud computing, networking is crucial because most Cloud services rely on the communication between various resources. There are users, a web server, a database server and a storage service to communicate with one another.

Resources can also be managed to regulate their communication through cloud networks. This can aid in organization, access and security when designing a cloud infrastructure.

### KillerCoda Environment

The IP addresses returned by the KillerCoda server were:

- **172.30.1.2**
- **172.17.0.1**

The addresses have been retrieved with the `hostname -I` command in the terminal. Address 172.30.1.2 was the primary IP address listed in the infrastructure report.

These IP addresses are indicative that the Linux server is plugged into a network within the KillerCoda environment. The networking architecture enables the server to interact with the surrounding world and other resources that are plugged in.

---

## 4. Operating System

### Purpose

An operating system is a program that controls the hardware functions of a computer and offers everything required for the application and service to operate. It serves as an access point between the hardware and software running on the server machine.

The operating system also offers tools to manage the files, processes, memory, storage, network connections and other resources of the system.

### Importance in Cloud Computing

The operating system is an important aspect of a cloud server since applications require some operating environment to run. The operating system also enables system administrators to configure and manage the server.

In cloud environments, Linux is widely used as it offers a reliable and stable server environment, and a set of command-line tools, which can be utilized for system administration and monitoring.

### KillerCoda Environment

The operating system detected in the KillerCoda operating system is: Ubuntu 24.04.4 LTS. The kernel version on the server is: 6.8.0-136-generic.

A number of Linux commands were used to analyse the system during the investigation. For instance, `cat /etc/os-release` was used to determine the operating system, and `uname -r` was used to verify the version of the kernel.

The terminal window for checking the CPU, RAM, Disk, mounted filesystems, hostname and ip addresses was also provided in Ubuntu Linux.

---

The components are associated with the one variable.All the components are related to one variable.

The four infrastructure components are linked together and are interdependent to form the server environment.

Compute – It is the power to run commands and applications.
Storage: Where the operating system, applications, and files are stored.
The server is able to communicate with other resources via **Networking**.
Operating System is a program that controls the hardware and provides the environment for applications and services.

These components can be observed functioning in the KillerCoda server. It is under Ubuntu control, using Intel Xeon CPU for processing, 19 GB disk for storage and assigned IP addresses for networking.
