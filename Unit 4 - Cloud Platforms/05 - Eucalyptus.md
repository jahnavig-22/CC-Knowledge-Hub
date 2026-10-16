# Eucalyptus Cloud Platform

## 1. Introduction

Eucalyptus is an open-source software platform used to build and manage private and hybrid clouds. Its name stands for **Elastic Utility Computing Architecture for Linking Your Programs To Useful Systems**.

It allows organizations to create a cloud environment using their own computing resources.

## 2. Main Components

- **Cloud Controller (CLC):** Manages the overall cloud and receives requests from users.
    
- **Cluster Controller (CC):** Manages groups of virtual machine instances within a cluster.
    
- **Node Controller (NC):** Controls virtual machine instances on individual physical machines.
    
- **Storage Controller (SC):** Provides storage services for virtual machine volumes.
    
- **Walrus:** Provides object storage in traditional Eucalyptus architecture.
    

## 3. Features

- Supports private cloud deployment.
    
- Uses an architecture based on cloud controllers and node controllers.
    
- Supports virtual machine management.
    
- Provides computing and storage resources.
    
- Offers compatibility with some Amazon EC2 and S3 interfaces in traditional versions.
    

## 4. How Eucalyptus Works

1. A user submits a request to create a virtual machine.
    
2. The Cloud Controller processes the request.
    
3. The Cluster Controller selects suitable computing resources.
    
4. The Node Controller starts the virtual machine on a physical host.
    
5. Storage components provide the required storage.
    

## 5. Advantages

- Helps organizations build private clouds.
    
- Allows the use of existing computing infrastructure.
    
- Supports virtual machine management.
    
- Provides control over an organization's cloud environment.
    

## 6. Limitations

- Setup and maintenance require technical knowledge.
    
- Managing the infrastructure can be complex.
    
- Available features and support depend on the version used.
    
- It may require more administration than a fully managed public cloud service.
    

## 7. Example

A college can use a private cloud platform such as Eucalyptus to provide virtual machines for student programming labs using its own servers.

## 8. Summary

Eucalyptus is a cloud software platform designed to help organizations build and manage private and hybrid cloud environments using their computing resources.

[[06 - OpenStack]]
