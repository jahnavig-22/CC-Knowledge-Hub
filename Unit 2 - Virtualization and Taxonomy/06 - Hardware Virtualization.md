# Hardware Virtualization

## 1. Definition

Hardware virtualization is a technique in which the physical hardware of a computer is abstracted to create virtual machines. A hypervisor manages the virtual machines and allocates physical hardware resources to them.

## 2. How Hardware Virtualization Works

1. The physical computer provides hardware resources such as CPU, memory, storage, and input/output devices.
    
2. The hypervisor creates and manages virtual machines.
    
3. Each virtual machine receives virtual hardware resources.
    
4. A guest operating system and its applications run inside each virtual machine.
    

## 3. Main Components

- **Physical Hardware:** The actual computer and its resources.
    
- **Hypervisor:** Software that creates and manages virtual machines.
    
- **Virtual Machine:** A software-based computer with virtual resources.
    
- **Guest Operating System:** The operating system running inside a virtual machine.
    

## 4. Advantages

- Allows multiple virtual machines to run on one physical computer.
    
- Improves hardware resource utilization.
    
- Provides isolation between virtual machines.
    
- Makes it easier to create and manage computing environments.
    

## 5. Example

A single physical server can run multiple virtual machines, with each machine running its own operating system and applications.

## 6. Simple Diagram

Physical Hardware  
↓  
Hypervisor  
↓  
Virtual Machines  
↓  
Guest Operating Systems and Applications

## 7. Summary

Hardware virtualization uses a hypervisor to create virtual machines from a physical computer's hardware resources. Each virtual machine can run its own operating system and applications.

[[07 - CPU Virtualization]]
