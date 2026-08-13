# ☁️ Cloud Provider Comparison

> **Laboratory 02 – Build the Cloud Infrastructure Blueprint**  
> A comparison of core infrastructure services offered by AWS, Microsoft Azure, and Google Cloud Platform.

---

## 🎯 Overview

AWS, Microsoft Azure, and Google Cloud Platform (GCP) are three major public cloud providers. They offer similar infrastructure services, but each provider has its own service names, tools, and features.

This comparison focuses on four basic cloud infrastructure components:

- 💻 **Compute**
- 💾 **Storage**
- 🌐 **Networking**
- 🔐 **Identity and Access Management (IAM)**

---

## 📊 Infrastructure Service Comparison

| Infrastructure Component | 🟧 AWS | 🔵 Microsoft Azure | 🔵 Google Cloud Platform |
|:---|:---|:---|:---|
| 💻 **Compute** | **Amazon EC2** | **Azure Virtual Machines** | **Compute Engine** |
| 💾 **Storage** | **Amazon S3** | **Azure Blob Storage** | **Cloud Storage** |
| 🌐 **Networking** | **Amazon VPC** | **Azure Virtual Network (VNet)** | **Cloud VPC** |
| 🔐 **IAM** | **AWS IAM** | **Microsoft Entra ID / Azure RBAC** | **Cloud IAM** |

---

# 💻 1. Compute

### 🟧 AWS — Amazon EC2

Amazon Elastic Compute Cloud (EC2) provides virtual computing resources in AWS. It allows users to create virtual servers and select resources based on the requirements of their applications.

### 🔵 Microsoft Azure — Azure Virtual Machines

Azure Virtual Machines provide virtual machines that run in the Azure cloud. They can be used to run applications and operating systems without requiring the organization to maintain physical servers.

### 🔵 Google Cloud — Compute Engine

Google Compute Engine provides virtual machine instances for running workloads in Google Cloud. Users can choose different machine configurations depending on the workload.

### 🔎 Comparison

All three services provide **virtual computing resources**. The main difference is the platform and the tools provided by each cloud provider.

---

# 💾 2. Storage

### 🟧 AWS — Amazon S3

Amazon S3 is an object storage service used to store and retrieve data. It uses buckets to organize stored objects.

### 🔵 Microsoft Azure — Azure Blob Storage

Azure Blob Storage is an object storage service designed for storing large amounts of unstructured data such as files, documents, images, and backups.

### 🔵 Google Cloud — Cloud Storage

Google Cloud Storage provides object storage for storing and accessing data in Google Cloud.

### 🔎 Comparison

All three services provide **cloud-based object storage**. They can be used to store files and other types of data without depending on local storage.

---

# 🌐 3. Networking

### 🟧 AWS — Amazon VPC

Amazon Virtual Private Cloud (VPC) allows users to create a logically isolated virtual network in AWS. It can contain resources such as subnets, routes, and gateways.

### 🔵 Microsoft Azure — Virtual Network

Azure Virtual Network (VNet) provides a private network for Azure resources. It allows resources to communicate with each other and with other networks.

### 🔵 Google Cloud — VPC

Google Cloud VPC provides networking for resources running in Google Cloud. It allows cloud resources to communicate within a virtual network.

### 🔎 Comparison

The three services provide **virtual networking** for cloud resources. They help organize communication between servers, applications, and other resources.

---

# 🔐 4. Identity and Access Management

### 🟧 AWS — AWS IAM

AWS Identity and Access Management (IAM) controls access to AWS resources. Administrators can assign permissions to users, roles, and applications.

### 🔵 Microsoft Azure — Microsoft Entra ID / Azure RBAC

Microsoft Entra ID provides identity and authentication services, while Azure Role-Based Access Control (RBAC) controls access to Azure resources based on assigned roles.

### 🔵 Google Cloud — Cloud IAM

Google Cloud IAM manages access to Google Cloud resources using roles and permissions. It helps control who can access resources and what actions they can perform.

### 🔎 Comparison

All three platforms provide **identity and access management**. Their purpose is similar: controlling who can access cloud resources and what they are allowed to do.

---

# 📝 Guide Questions

## 1. Which cloud provider offers the broadest range of services?

AWS is generally considered to have one of the broadest selections of cloud services. It provides services covering computing, storage, networking, databases, security, analytics, development, and many other areas.

## 2. Which cloud platform would you recommend for an organization that primarily uses Microsoft products?

I would recommend **Microsoft Azure** for an organization that primarily uses Microsoft products. Azure works closely with Microsoft's existing technologies and identity services, making it a practical choice for organizations already using the Microsoft ecosystem.

## 3. Which platform is widely recognized for Artificial Intelligence (AI), Machine Learning (ML), and Kubernetes services?

**Google Cloud** is widely recognized for its strengths in Artificial Intelligence, Machine Learning, and Kubernetes. Google Kubernetes Engine (GKE) provides a managed Kubernetes environment for deploying and managing containerized applications.

## 4. What similarities did you observe among the three cloud providers?

The three providers offer similar basic infrastructure services, including compute, storage, networking, and identity management. Although the service names and features differ, their main purpose is similar: providing scalable resources that organizations can use without maintaining all of the physical infrastructure themselves.

---

# 📚 Official Documentation

The following official documentation was used for the comparison:

### 🟧 Amazon Web Services

- [Amazon EC2 Documentation](https://docs.aws.amazon.com/ec2/)
- [Amazon S3 Documentation](https://docs.aws.amazon.com/s3/)
- [Amazon VPC Documentation](https://docs.aws.amazon.com/vpc/)
- [AWS IAM Documentation](https://docs.aws.amazon.com/iam/)

### 🔵 Microsoft Azure

- [Azure Virtual Machines](https://learn.microsoft.com/azure/virtual-machines/)
- [Azure Blob Storage](https://learn.microsoft.com/azure/storage/blobs/)
- [Azure Virtual Network](https://learn.microsoft.com/azure/virtual-network/)
- [Microsoft Entra ID](https://learn.microsoft.com/entra/identity/)

### 🔵 Google Cloud

- [Compute Engine Documentation](https://cloud.google.com/compute/docs)
- [Cloud Storage Documentation](https://cloud.google.com/storage/docs)
- [VPC Documentation](https://cloud.google.com/vpc/docs)
- [IAM Documentation](https://cloud.google.com/iam/docs)
- [Google Kubernetes Engine](https://cloud.google.com/kubernetes-engine/docs)

---

> **💡 Key Takeaway:**  
> Although AWS, Azure, and Google Cloud use different service names and tools, they provide the same fundamental building blocks needed to create cloud infrastructure: **compute, storage, networking, and access management.**
