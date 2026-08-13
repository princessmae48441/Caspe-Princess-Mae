# Cloud Infrastructure Components

## 1. Compute Resources

### Purpose

Compute resources provide the processing power needed to run the operating system, applications, and commands on a server. The CPU is one of the main resources responsible for processing instructions.

### Importance in Cloud Computing

Compute resources are important because cloud applications need processing power to operate. Cloud platforms allow organizations to choose and adjust compute resources depending on the workload and requirements of their applications.

### KillerCoda Environment

In the KillerCoda environment, the server is using an **Intel Xeon E312xx (Sandy Bridge, IBRS update)** CPU with **1 CPU core**. This CPU is the compute resource available to the Linux server and is responsible for processing the commands and services running in the environment.

---

## 2. Storage Resources

### Purpose

Storage resources are used to store the operating system, applications, configuration files, and other data needed by the server.

### Importance in Cloud Computing

Storage is important in cloud computing because applications and services need a place to keep their data. Cloud storage can also be expanded or managed based on the needs of an organization.

### KillerCoda Environment

The KillerCoda server has a main disk, **`/dev/vda1`**, with a capacity of **19 GB**. It is mounted at `/` and uses the **ext4** file system. During the investigation, **5.4 GB was used** and around **13 GB was available**.

---

## 3. Networking Resources

### Purpose

Networking resources allow the server to communicate with other devices, services, and networks. They are used to send and receive data between systems.

### Importance in Cloud Computing

Networking is important because cloud servers need to communicate with users, applications, databases, and other cloud services. A properly configured network also allows resources to be accessed and managed within a cloud environment.

### KillerCoda Environment

The KillerCoda server has the IP addresses **172.30.1.2** and **172.17.0.1**. These addresses were displayed using the `hostname -I` command. The IP addresses show that the Linux server is connected to a network and can communicate within its provided environment.

---

## 4. Operating System

### Purpose

The operating system manages the computer's hardware and provides the environment needed to run applications and services. It also provides tools and commands for managing the server.

### Importance in Cloud Computing

The operating system is important in cloud computing because cloud servers need an operating environment where applications and services can run. It also allows administrators to manage resources, configure the server, and monitor its performance.

### KillerCoda Environment

The KillerCoda server is running **Ubuntu 24.04.4 LTS** with kernel version **6.8.0-136-generic**. The Linux environment provides the terminal and system commands used during the investigation, such as `uname`, `lscpu`, `free`, `df`, `findmnt`, and `hostname`.

---

## Overall Observation

The four components work together to provide a functional cloud server environment. The **CPU** provides processing power, the **disk** provides storage, the **network** allows communication, and the **operating system** manages the resources and provides the environment where services can run.

The KillerCoda server is a simple example of how these basic infrastructure components are combined in a cloud environment.
