# Cloud Provider Comparison

## Overview

Amazon Web Services (AWS), Microsoft Azure, and Google Cloud Platform (GCP) are major public cloud providers. They provide similar cloud infrastructure services, but the services have different names and may offer different features.

This comparison focuses on four major infrastructure components: compute, storage, networking, and identity and access management (IAM).

---

## Infrastructure Service Comparison

| Infrastructure Component | AWS | Microsoft Azure | Google Cloud Platform |
|---|---|---|---|
| **Compute** | Amazon EC2 | Azure Virtual Machines | Google Compute Engine |
| **Storage** | Amazon S3 | Azure Blob Storage | Google Cloud Storage |
| **Networking** | Amazon VPC | Azure Virtual Network (VNet) | Google Cloud VPC |
| **Identity and Access Management (IAM)** | AWS IAM | Microsoft Entra ID / Azure RBAC | Google Cloud IAM |

---

## 1. Compute

### AWS – Amazon EC2

Amazon Elastic Compute Cloud (EC2) provides virtual computing resources in AWS. It allows users to create virtual servers and select computing resources based on the requirements of their applications and workloads.

### Microsoft Azure – Azure Virtual Machines

Azure Virtual Machines provide virtual machines that run in the Azure cloud environment. They can be used to run applications and operating systems without requiring an organization to maintain physical servers.

### Google Cloud – Google Compute Engine

Google Compute Engine provides virtual machine instances for running applications and workloads in Google Cloud. Users can select different machine configurations depending on their computing requirements.

### Comparison

All three services provide virtual computing resources. They allow organizations to run applications and workloads using cloud-based virtual machines instead of depending entirely on physical servers.

---

## 2. Storage

### AWS – Amazon S3

Amazon Simple Storage Service (S3) is an object storage service used to store and retrieve data. Data is stored as objects inside containers called buckets.

### Microsoft Azure – Azure Blob Storage

Azure Blob Storage is Microsoft's object storage service. It can be used to store large amounts of unstructured data such as documents, images, videos, and backups.

### Google Cloud – Google Cloud Storage

Google Cloud Storage provides object storage for storing and accessing data in Google Cloud. It can be used by applications and other cloud resources that need to store files and objects.

### Comparison

The three providers offer object storage services for storing data in the cloud. Although the names and management tools are different, their main purpose is to provide reliable storage that can be accessed by applications and users.

---

## 3. Networking

### AWS – Amazon VPC

Amazon Virtual Private Cloud (VPC) allows users to create a logically isolated virtual network in AWS. It can include networking components such as subnets, route tables, and gateways.

### Microsoft Azure – Azure Virtual Network

Azure Virtual Network (VNet) provides a private network for resources running in Azure. It allows resources to communicate with each other and with other networks.

### Google Cloud – Google Cloud VPC

Google Cloud VPC provides networking capabilities for resources running in Google Cloud. It allows cloud resources to communicate within a virtual network.

### Comparison

All three providers offer virtual networking services that allow cloud resources to communicate with each other. These services are important when designing a cloud infrastructure because applications and servers often need to communicate securely.

---

## 4. Identity and Access Management (IAM)

### AWS – AWS IAM

AWS Identity and Access Management (IAM) is used to control access to AWS resources. It allows administrators to manage users, roles, and permissions.

### Microsoft Azure – Microsoft Entra ID / Azure RBAC

Microsoft Entra ID provides identity and authentication services in the Microsoft cloud environment. Azure Role-Based Access Control (RBAC) can be used to manage permissions for Azure resources.

### Google Cloud – Google Cloud IAM

Google Cloud IAM controls access to Google Cloud resources through roles and permissions. It helps administrators determine who can access resources and what actions they are allowed to perform.

### Comparison

The three cloud providers have identity and access management services that help organizations control access to their cloud resources. Their main purpose is to make sure that users and applications receive the appropriate permissions.

---

# Guide Questions

## 1. Which cloud provider offers the broadest range of services? Explain your answer.

AWS is generally considered to have one of the broadest selections of cloud services. It provides services for computing, storage, networking, databases, security, analytics, application development, and many other cloud workloads.

## 2. Which cloud platform would you recommend for an organization that primarily uses Microsoft products? Why?

I would recommend Microsoft Azure for an organization that primarily uses Microsoft products. Azure works closely with Microsoft's existing technologies and identity services, which can make it easier to connect existing Microsoft systems with cloud resources.

## 3. Which platform is widely recognized for Artificial Intelligence (AI), Machine Learning (ML), and Kubernetes services?

Google Cloud is widely recognized for its strengths in Artificial Intelligence, Machine Learning, and Kubernetes services. Google Kubernetes Engine (GKE) provides a managed Kubernetes environment for deploying and managing containerized applications.

## 4. What similarities did you observe among the three cloud providers?

The three cloud providers offer similar basic infrastructure services, including compute, storage, networking, and identity and access management. The main differences are their service names, features, management tools, and integration with their respective cloud platforms.

---

# Official Documentation Sources

## AWS

- [Amazon EC2 Documentation](https://docs.aws.amazon.com/ec2/)
- [Amazon S3 Documentation](https://docs.aws.amazon.com/s3/)
- [Amazon VPC Documentation](https://docs.aws.amazon.com/vpc/)
- [AWS IAM Documentation](https://docs.aws.amazon.com/iam/)

## Microsoft Azure

- [Azure Virtual Machines Documentation](https://learn.microsoft.com/azure/virtual-machines/)
- [Azure Blob Storage Documentation](https://learn.microsoft.com/azure/storage/blobs/)
- [Azure Virtual Network Documentation](https://learn.microsoft.com/azure/virtual-network/)
- [Microsoft Entra ID Documentation](https://learn.microsoft.com/entra/identity/)

## Google Cloud Platform

- [Compute Engine Documentation](https://cloud.google.com/compute/docs)
- [Cloud Storage Documentation](https://cloud.google.com/storage/docs)
- [Google Cloud VPC Documentation](https://cloud.google.com/vpc/docs)
- [Google Cloud IAM Documentation](https://cloud.google.com/iam/docs)
- [Google Kubernetes Engine Documentation](https://cloud.google.com/kubernetes-engine/docs)
