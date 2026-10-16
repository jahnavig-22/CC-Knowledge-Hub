# Full Virtualization

## 1. Definition

Full virtualization is a virtualization technique in which the hypervisor provides a complete virtual hardware environment to the guest operating system. The guest operating system does not need to be modified to run inside the virtual machine.

## 2. How Full Virtualization Works

1. The hypervisor creates a virtual hardware environment.
    
2. A guest operating system is installed inside the virtual machine.
    
3. The guest OS works as if it is running on a physical computer.
    
4. The hypervisor manages the virtual machine's access to physical hardware resources.
    

## 3. Features of Full Virtualization

- Provides a complete virtual hardware environment.
    
- The guest operating system remains unmodified.
    
- The guest OS is unaware that it is running in a virtualized environment.
    
- The hypervisor manages hardware resources.
    
- Multiple virtual machines can run on one physical machine.
    

## 4. Examples

- VMware ESXi
    
- Microsoft Hyper-V
    

## 5. Advantages

- Supports unmodified guest operating systems.
    
- Allows multiple virtual machines to run on one physical computer.
    
- Provides isolation between virtual machines.
    
- Helps use hardware resources efficiently.
    

## 6. Simple Diagram

Physical Hardware  
↓  
Hypervisor  
↓  
Virtual Machine  
↓  
Guest Operating System  
↓  
Applications

## 7. Summary

Full virtualization creates a complete virtual hardware environment using a hypervisor. The guest operating system does not need modification and operates as if it is running on a physical computer.

[[05 - Para Virtualization]]
