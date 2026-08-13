# Cloud Provider Comparison

## Introduction

AWS, Microsoft Azure, and Google Cloud Platform (GCP) are major public cloud providers. They offer similar infrastructure services, but each provider uses its own service names and has different features.

This comparison focuses on four basic infrastructure components: compute, storage, networking, and identity and access management.

## Infrastructure Service Comparison

| Infrastructure Component | AWS | Microsoft Azure | Google Cloud Platform |
|---|---|---|---|
| **Compute** | Amazon EC2 | Azure Virtual Machines | Google Compute Engine |
| **Storage** | Amazon S3 | Azure Blob Storage | Google Cloud Storage |
| **Networking** | Amazon VPC | Azure Virtual Network (VNet) | Google Cloud VPC |
| **Identity and Access Management (IAM)** | AWS IAM | Microsoft Entra ID / Azure RBAC | Google Cloud IAM |

## Service Comparison

### Compute

**Amazon EC2** provides virtual computing resources in AWS. It allows users to create and run virtual servers for applications and other workloads.

**Azure Virtual Machines** provide virtual machines that run in the Azure cloud. They can be used to run applications and operating systems without maintaining physical servers.

**Google Compute Engine** provides virtual machine instances that can be used to run workloads on Google Cloud.

These three services serve a similar purpose because they provide the computing resources needed to run applications and workloads in the cloud.

### Storage

**Amazon S3** is an object storage service used to store and retrieve data. Data is stored as objects inside S3 buckets.

**Azure Blob Storage** is Azure's object storage service. It can be used to store different types of unstructured data such as files, documents, images, and backups.

**Google Cloud Storage** provides object storage for data and files in Google Cloud.

The three services provide cloud-based storage, although their service names, features, and management interfaces are different.

### Networking

**Amazon VPC** provides a logically isolated virtual network in AWS. It allows cloud resources such as EC2 instances to communicate using configured subnets, routes, and other networking resources.

**Azure Virtual Network (VNet)** provides a private network for Azure resources. It can be used to organize resources and control communication between them.

**Google Cloud VPC** provides networking for Google Cloud resources such as Compute Engine virtual machines and Google Kubernetes Engine workloads.

All three services provide virtual networking capabilities that allow cloud resources to communicate with each other.

### Identity and Access Management (IAM)

**AWS IAM** is used to manage access to AWS resources. It allows administrators to control which users, roles, and applications can access specific resources and what actions they can perform.

**Microsoft Entra ID** provides identity and authentication services in the Microsoft cloud environment, while **Azure RBAC** is used to assign permissions to Azure resources.

**Google Cloud IAM** controls who can access Google Cloud resources and what actions they are allowed to perform through roles and permissions.

The three providers all provide identity and access management features to help control access to cloud resources.

---

# Guide Questions

## 1. Which cloud provider offers the broadest range of services? Explain your answer.

AWS is generally considered to have one of the broadest selections of cloud services. It provides services for computing, storage, networking, databases, security, analytics, development, and many other cloud workloads.

## 2. Which cloud platform would you recommend for an organization that primarily uses Microsoft products? Why?

I would recommend Microsoft Azure for an organization that primarily uses Microsoft products. Azure works closely with Microsoft's technologies and identity services, which can make it easier to connect existing Microsoft systems with cloud resources.

## 3. Which platform is widely recognized for Artificial Intelligence (AI), Machine Learning (ML), and Kubernetes services?

Google Cloud is widely recognized for its work in Artificial Intelligence, Machine Learning, and Kubernetes. Google Kubernetes Engine (GKE) provides a managed Kubernetes environment for deploying, managing, and scaling containerized applications.

## 4. What similarities did you observe among the three cloud providers?

The three cloud providers offer similar basic infrastructure services, including virtual machines, cloud storage, networking, and identity and access management. The main differences are their service names, specific features, management tools, and the way their services are integrated with their respective cloud platforms.

---

# Official Documentation Sources

- AWS EC2: https://docs.aws.amazon.com/ec2/
- AWS S3: https://docs.aws.amazon.com/s3/
- AWS VPC: https://docs.aws.amazon.com/vpc/
- AWS IAM: https://docs.aws.amazon.com/iam/

- Azure Virtual Machines: https://learn.microsoft.com/azure/virtual-machines/
- Azure Blob Storage: https://learn.microsoft.com/azure/storage/blobs/
- Azure Virtual Network: https://learn.microsoft.com/azure/virtual-network/
- Microsoft Entra ID: https://learn.microsoft.com/entra/identity/

- Google Compute Engine: https://cloud.google.com/compute/docs
- Google Cloud Storage: https://cloud.google.com/storage/docs
- Google Cloud VPC: https://cloud.google.com/vpc/docs
- Google Cloud IAM: https://cloud.google.com/iam/docs
- Google Kubernetes Engine: https://cloud.google.com/kubernetes-engine/docs
