 Linux Server Investigation

## 1. Operating System

The Linux server is running:

- **Operating System:** Ubuntu 24.04.4 LTS
- **Version:** Ubuntu 24.04 (Noble Numbat)
- **Architecture:** x86_64
- **Kernel:** Linux 6.8.0-136-generic

The operating system was identified using:

```bash
cat /etc/os-release
```

---

## 2. CPU Information

The server's CPU information was identified using:

```bash
lscpu
```

### CPU Details

- **CPU Model:** Intel Xeon E312xx (Sandy Bridge, IBRS update)
- **Architecture:** x86_64
- **CPU(s):** 1
- **Core(s) per socket:** 1
- **Thread(s) per core:** 1
- **Socket(s):** 1
- **Virtualization:** KVM
- **CPU Frequency:** 2.0 GHz

The server has **1 virtual CPU core** available.

---

## 3. Memory

The memory information was identified using:

```bash
free -h
```

### Memory Details

| Resource | Amount |
|---|---:|
| Total RAM | 1.9 GiB |
| Used RAM | 429 MiB |
| Free RAM | 850 MiB |
| Available RAM | 1.4 GiB |
| Swap | 1.0 GiB |
| Swap Used | 0 B |

The server has approximately **1.9 GiB of RAM** and **1.0 GiB of swap space**.

---

## 4. Disk Space

The disk information was identified using:

```bash
df -h
```

### Main Disk

| Filesystem | Size | Used | Available | Usage |
|---|---:|---:|---:|---:|
| /dev/vda1 | 19 GB | 5.4 GB | 13 GB | 30% |

The main filesystem has **19 GB of total storage**, with approximately **13 GB available**.

The server also contains separate partitions for `/boot` and `/boot/efi`.

---

# 5. Cloud Migration Options

If this Linux server were migrated to the cloud, it could be hosted using virtual machine or compute services from AWS, Azure, and GCP.

| Cloud Provider | Service | Purpose |
|---|---|---|
| **AWS** | Amazon EC2 | Hosts the Ubuntu Linux server as a virtual machine |
| **Azure** | Azure Virtual Machines | Runs Ubuntu Linux as a cloud virtual machine |
| **GCP** | Compute Engine | Runs the Ubuntu Linux server as a virtual machine |

### AWS – Amazon EC2

**Amazon Elastic Compute Cloud (EC2)** would be an appropriate choice because it provides resizable virtual servers in the cloud. The existing Ubuntu server could be migrated to an EC2 instance with suitable CPU, memory, and storage resources.

### Azure – Azure Virtual Machines

**Azure Virtual Machines** can host Ubuntu Linux servers in the cloud. A VM size with approximately 1 vCPU and 2 GB of RAM could provide resources similar to the current server, depending on the available VM options and workload requirements.

### GCP – Compute Engine

**Google Compute Engine** provides configurable virtual machines that can run Ubuntu Linux. A small machine configuration could be selected to provide resources comparable to the current server.

---

# 6. Migration Summary

The current Linux server has:

- **Ubuntu 24.04.4 LTS**
- **1 CPU core**
- **1.9 GiB RAM**
- **19 GB disk**
- **KVM virtualization**

A suitable cloud migration would therefore be a **small Linux virtual machine** on any of the three major cloud providers:

- **AWS → Amazon EC2**
- **Azure → Azure Virtual Machines**
- **GCP → Compute Engine**

The exact cloud instance/VM size should ultimately be selected based on the server's workload, performance requirements, expected traffic, and budget.

---

# 7. Terminal Output Screenshots

The following screenshot contains the terminal output from the KillerCoda Linux server investigation.

![KillerCoda Terminal Output](screenshots/killercode-terminal.png)
