# Unit 2 – Virtualization Structure and Implementation Levels

## 1. What is Virtualization?

**Virtualization** is a technology that creates virtual versions of computing resources, allowing multiple virtual environments to share the resources of a physical computer.

## 2. Structure of Virtualization

A basic virtualization system can be understood through these layers:

1. **Physical Hardware:** The CPU, RAM, storage and network devices of the physical computer.
    
2. **Hypervisor:** The software layer that creates and manages virtual machines.
    
3. **Virtual Machines:** Virtual computers that share the physical hardware.
    
4. **Guest Operating Systems:** Operating systems installed inside the virtual machines.
    
5. **Applications:** Programs that run inside each guest operating system.
    

### Simple Diagram

Physical Hardware  
↓  
Hypervisor  
↓  
Virtual Machines  
↓  
Guest Operating Systems  
↓  
Applications

_Note: This is a simplified structure. The exact arrangement depends on the virtualization method._

## 3. Virtualization Implementation Levels

Implementation levels describe the different layers at which virtualization can be provided.

### A. Instruction Set Architecture (ISA) Level

- Works at the processor instruction level.
    
- Uses instruction translation or emulation.
    
- Can support software designed for different processor architectures.
    
- May have additional processing overhead.
    

**Example:** QEMU can emulate different hardware architectures.

### B. Hardware-Level Virtualization

- Uses a hypervisor to create virtual machines on physical hardware.
    
- Each VM can run its own operating system.
    
- The hypervisor manages CPU, memory and other resources.
    

**Example:** VMware ESXi.

### C. Operating System-Level Virtualization

- Creates multiple isolated environments that share the same operating system kernel.
    
- These environments are commonly called containers.
    
- Containers are generally lightweight and start quickly.
    

**Example:** Docker containers.

### D. Library Support-Level Virtualization

- Uses compatibility libraries to provide interfaces expected by applications.
    
- Helps certain applications designed for one environment work in another.
    
- Compatibility depends on the application and the libraries supported.
    

**Example:** Wine provides compatibility for many Windows applications on Linux.

### E. Application-Level Virtualization

- Provides an isolated environment for individual applications.
    
- Can simplify application deployment.
    
- Can reduce conflicts between applications.
    

**Example:** Applications delivered through application-virtualization software.

## 4. Advantages of Virtualization

- Efficient use of physical hardware.
    
- Ability to run separate computing environments.
    
- Useful for software testing and development.
    
- Flexible allocation of computing resources.
    
- Easier management of virtual environments.
    

## Quick Revision

- **Virtualization:** Creating virtual computing environments.
    
- **Hypervisor:** Manages virtual machines.
    
- **ISA level:** Works with processor instructions.
    
- **Hardware level:** Uses a hypervisor to create VMs.
    
- **OS level:** Creates containers sharing an OS kernel.
    
- **Library support level:** Uses compatibility libraries.
    
- **Application level:** Provides an isolated environment for applications.

[[04 - Full Virtualization]]
