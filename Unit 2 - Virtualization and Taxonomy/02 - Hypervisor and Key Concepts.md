# Unit 2 – Hypervisor and Key Concepts

## 1. Definition of Hypervisor

A **hypervisor**, also called a **Virtual Machine Monitor (VMM)**, is software or firmware that creates and manages virtual machines by allocating physical hardware resources.

## 2. Functions of a Hypervisor

- Creates and manages virtual machines.
    
- Allocates CPU, memory and storage resources.
    
- Manages the execution of multiple VMs.
    
- Provides isolation between virtual machines.
    
- Connects virtual resources to physical hardware.
    

## 3. Types of Hypervisors

### A. Type 1 – Bare-Metal Hypervisor

A Type 1 hypervisor runs directly on the physical hardware.

**Features:**

- Runs without a general-purpose host operating system beneath it.
    
- Commonly used in servers and data centres.
    
- Manages resources for multiple virtual machines.
    
- Is suitable for server virtualization.
    

**Examples:** VMware ESXi and Xen.

### B. Type 2 – Hosted Hypervisor

A Type 2 hypervisor runs as an application on an existing operating system.

**Features:**

- Easy to install on a personal computer.
    
- Useful for learning, software development and testing.
    
- Depends on the host operating system.
    
- Adds an extra software layer between the VM and physical hardware.
    

**Examples:** Oracle VirtualBox and VMware Workstation.

## 4. Difference Between Type 1 and Type 2 Hypervisors

|Type 1 Hypervisor|Type 2 Hypervisor|
|---|---|
|Runs directly on physical hardware.|Runs on a host operating system.|
|Commonly used in servers and data centres.|Commonly used on personal computers.|
|Suitable for managing server workloads.|Suitable for learning and testing.|
|Example: VMware ESXi.|Example: Oracle VirtualBox.|

## 5. Important Concepts

**Host Machine:** The physical computer that provides hardware resources.

**Guest Machine:** The virtual computer running on the host.

**Guest OS:** The operating system installed inside a virtual machine.

**Virtual Machine Monitor (VMM):** Another name for a hypervisor.

**Resource Allocation:** Assigning CPU, memory and storage resources to virtual machines.

**Isolation:** Keeping virtual machines separated from one another.

## 6. Real-Life Example

A company has one powerful physical server and needs separate environments for its website, database and testing work.

A hypervisor creates three virtual machines and allocates resources to each one. Each VM can run its own operating system and applications while sharing the physical server.

## Quick Revision

- A hypervisor creates and manages virtual machines.
    
- Type 1 runs directly on physical hardware.
    
- Type 2 runs on a host operating system.
    
- VMM stands for Virtual Machine Monitor.
    
- Resource allocation and isolation are important hypervisor functions.

[[03 - Virtualization Structure and Implementation Levels]]
