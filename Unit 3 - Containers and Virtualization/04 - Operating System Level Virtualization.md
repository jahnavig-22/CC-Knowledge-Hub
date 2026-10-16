# Operating System Level Virtualization

## 1. Definition

Operating System Level Virtualization is a virtualization technique in which a single operating system kernel is used to run multiple isolated environments called **containers**.

Each container behaves like an independent system, but all containers share the host operating system's kernel.

**Example:** Docker allows multiple applications to run inside separate containers on one computer without requiring a separate operating system for each application.

## 2. How It Works

1. A physical computer runs a host operating system.
    
2. The operating system kernel manages system resources.
    
3. Virtualization software creates separate containers.
    
4. Each container has its own applications, libraries and dependencies.
    
5. Containers share the host operating system kernel while remaining isolated from one another.
    

## 3. Main Features

- **Lightweight:** Containers require fewer resources than virtual machines.
    
- **Isolation:** Applications run in separate environments.
    
- **Fast startup:** Containers can start quickly.
    
- **Resource sharing:** Containers share the host operating system kernel.
    
- **Portability:** Containers can be moved between compatible environments.
    

## 4. Advantages

1. Uses less memory and storage.
    
2. Starts applications quickly.
    
3. Allows multiple applications to run on one host.
    
4. Improves resource utilization.
    
5. Makes application deployment easier.
    

## 5. Disadvantages

1. Containers must use a kernel compatible with the host operating system.
    
2. A host kernel failure can affect multiple containers.
    
3. Isolation may be weaker than the separation provided by full virtual machines.
    
4. Incorrect configuration can create security risks.
    

## 6. Real-Time Example

Suppose a company runs three applications: a website, a database and a payment service.

Using operating system level virtualization, the company can run each application in a separate container on the same server. Each container has its own dependencies, but all three share the host operating system kernel.

This saves resources and makes application management easier.

## 7. Difference Between OS-Level Virtualization and Virtual Machines

|OS-Level Virtualization|Virtual Machines|
|---|---|
|Containers share the host kernel.|Each VM runs its own guest operating system.|
|Lightweight.|Generally requires more resources.|
|Starts quickly.|Usually takes longer to start.|
|Provides process-level isolation.|Provides hardware-level virtualization and stronger OS separation.|

## 8. Summary

Operating System Level Virtualization creates isolated containers that share a common operating system kernel. It is lightweight, fast and resource-efficient. Docker is a popular technology that uses containers for application deployment.

[[05 - Application Virtualization]]
