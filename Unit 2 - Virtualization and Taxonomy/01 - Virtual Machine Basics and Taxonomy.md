# Unit 2 – Virtual Machine Basics and Taxonomy

## 1. Definition of Virtual Machine

A **Virtual Machine (VM)** is a software-based computer that behaves like a real computer. It has virtual CPU, memory, storage, network, an operating system and applications.

**Example:** Running a Linux virtual machine inside a Windows PC using VirtualBox or VMware.

## 2. Working of a Virtual Machine

A virtual machine works with the help of virtualization technology and a hypervisor.

1. **Physical computer starts:** The computer has CPU, RAM, storage and network hardware.
    
2. **Hypervisor manages resources:** The hypervisor manages the virtual machines.
    
3. **VM is created:** Virtual CPU, RAM, disk and network resources are assigned.
    
4. **Guest OS is installed:** An operating system such as Windows or Ubuntu is installed inside the VM.
    
5. **Applications run:** Programs run inside the guest operating system.
    
6. **Resources are provided:** The hypervisor connects the VM's virtual resources to the physical hardware.
    
7. **Multiple VMs operate:** One physical server can run several virtual machines.
    

## 3. Components of a Virtual Machine

- **Virtual CPU:** Provides processing resources.
    
- **Virtual Memory:** Provides memory to the VM.
    
- **Virtual Disk:** Stores files, applications and the operating system.
    
- **Network Interface Card (NIC):** Enables network communication.
    
- **Guest Operating System:** The OS installed inside the VM.
    

## 4. Uses of Virtual Machines

- Running Windows and Linux on the same computer.
    
- Practising operating systems and programming.
    
- Testing software without affecting the main environment.
    
- Running websites and databases on separate VMs.
    
- Running older software that needs an older operating system.
    
- Using physical server resources efficiently.
    

## 5. Taxonomy of Virtual Machines

**Taxonomy of Virtual Machines** means the classification of virtual machines into different types based on their purpose.

There are two main types:

### A. System Virtual Machine

A system virtual machine creates a complete virtual computer and runs a full operating system.

**Features:**

- Provides virtual hardware resources.
    
- Runs a complete guest operating system.
    
- Can run applications inside that operating system.
    
- Multiple system VMs can share one physical computer.
    

**Examples:** An Ubuntu VM running in VirtualBox or a virtual server running on AWS EC2.

### B. Process Virtual Machine

A process virtual machine provides an environment to run a particular application or program.

**Features:**

- Supports the execution of an individual program.
    
- Usually exists while the program is running.
    
- Can help programs run across different platforms when the appropriate runtime is available.
    

**Example:** Java Virtual Machine (JVM), which executes Java bytecode.

## 6. Difference Between System VM and Process VM

|System Virtual Machine|Process Virtual Machine|
|---|---|
|Runs a complete operating system.|Runs an individual program or process.|
|Provides virtual hardware resources.|Provides a program execution environment.|
|Can run many applications inside its guest OS.|Supports the particular program running in its environment.|
|Example: VirtualBox VM.|Example: Java Virtual Machine (JVM).|

## Quick Revision

- **VM:** A software-based computer.
    
- **Hypervisor:** Software that manages virtual machines.
    
- **Guest OS:** The operating system installed inside a VM.
    
- **System VM:** Runs a complete operating system.
    
- **Process VM:** Provides an environment for an individual program.
    
- **Taxonomy:** Classification into different types.

[[02 - Hypervisor and Key Concepts]]
