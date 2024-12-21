# Azure_Storage
Azure Storage

Guidance 
https://microsoftlearning.github.io/AZ-204-DevelopingSolutionsforMicrosoftAzure/Instructions/Labs/AZ-204_lab_03.html

Solution: 
https://github.com/utpal-maiti/AZ-204-DevelopingSolutionsforMicrosoftAzure/tree/master/Allfiles/Labs/03

**Azure Storage** is a cloud storage solution from Microsoft that offers highly available, secure, durable, and scalable storage. It provides various storage services to cater to different types of data storage needs. Here are the key components and features:

### Key Components of Azure Storage

1. **Blob Storage**:
   - **Purpose**: Stores unstructured data such as documents, images, videos, backups, and big data.
   - **Types**: Supports three types of blobs—Block blobs (text and binary data), Append blobs (append-only operations), and Page blobs (random read/write operations).

2. **File Storage**:
   - **Purpose**: Provides fully managed file shares in the cloud, accessible via the SMB protocol.
   - **Use Cases**: Lift and shift legacy applications, file sharing across multiple systems, and storage for applications.

3. **Queue Storage**:
   - **Purpose**: Stores large numbers of messages that can be accessed from anywhere.
   - **Use Cases**: Decouple and scale components of cloud applications, build reliable messaging and background task processing.

4. **Table Storage**:
   - **Purpose**: Stores structured NoSQL data in the cloud, providing a key/attribute store with a schema-less design.
   - **Use Cases**: Web applications, storing metadata, configuration data, or device information.

5. **Disk Storage**:
   - **Purpose**: Provides persistent, high-performance disk storage for Azure virtual machines.
   - **Types**: Standard HDD, Standard SSD, and Premium SSD, each optimized for different performance and cost needs.

### Key Features

- **Scalability**: Automatically scales to meet your storage needs.
- **Durability**: Offers up to 99.999999999% (11 nines) durability for data stored across regions.
- **Security**: Provides encryption at rest, managed keys, and access control via Azure Active Directory integration.
- **Global Distribution**: Enables geo-redundant storage options to replicate data across multiple regions for high availability.
- **Performance Tiers**: Offers different performance tiers to optimize for cost and performance based on workload requirements.

### Getting Started with Azure Storage

To start using Azure Storage, you can follow these general steps:

1. **Create a Storage Account**:
   - Go to the [Azure portal](https://portal.azure.com/).
   - Navigate to "Storage accounts" and click "Add".
   - Configure the necessary settings like subscription, resource group, storage account name, and performance options.
   - Click "Review + create" and then "Create" to provision the storage account.

2. **Use Storage Services**:
   - **Blob Storage**: Upload, download, and manage blobs using Azure Storage Explorer, the Azure portal, or programmatically using SDKs.
   - **File Storage**: Create and manage file shares using the Azure portal, CLI, or SDKs.
   - **Queue Storage**: Enqueue and dequeue messages using the Azure Storage SDKs.
   - **Table Storage**: Insert, query, and manage entities in table storage using the Azure Storage SDKs.
   - **Disk Storage**: Attach managed disks to virtual machines in the Azure portal or using PowerShell/CLI.

### Summary

Azure Storage provides a versatile and robust solution for all your cloud storage needs, from unstructured data and files to messaging and NoSQL databases. It's designed to be secure, scalable, and highly available, supporting a wide range of applications and use cases.


