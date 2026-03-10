# Project 2 — Azure Storage and Backup

## Overview

This project demonstrates the deployment and configuration of Azure Storage services to securely store and manage files in the cloud. The goal of this lab is to gain hands-on experience with Azure Storage Accounts, Blob Containers, and secure file access using Shared Access Signatures (SAS).

Azure Storage is a core component of many cloud architectures and is commonly used for application data, backups, logs, and file hosting.

---

## Skills Demonstrated

- Creating Azure Storage Accounts
- Configuring Blob Storage containers
- Uploading and managing objects (blobs)
- Implementing secure access using Shared Access Signatures (SAS)
- Understanding Azure object storage architecture
- Applying basic storage security practices

---

## Architecture

Azure Subscription  
│  
└── Resource Group  
  └── Storage Account  
    └── Blob Container  
      └── Uploaded Files (Blobs)

---

## Steps Performed

1. Created an Azure Storage Account within an existing resource group.
2. Configured the storage account with Standard performance and Locally Redundant Storage (LRS).
3. Created a private Blob container for storing files.
4. Uploaded files into the container to simulate application or backup storage.
5. Generated a Shared Access Signature (SAS) link to allow temporary secure access to stored files.

---

## Security Concept Demonstrated

This lab demonstrates **secure file sharing using Shared Access Signatures (SAS)**, which allows temporary and limited access to storage resources without exposing account keys.

This approach follows the **principle of least privilege** by granting only the necessary permissions for a limited time.

---

## Result

The storage account successfully hosts files within a private blob container. Secure access to files can be granted using SAS tokens without exposing the underlying storage account credentials.

---

## Technologies Used

- Microsoft Azure
- Azure Storage Accounts
- Azure Blob Storage
- Shared Access Signatures (SAS)
