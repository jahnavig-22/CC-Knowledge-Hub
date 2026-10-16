# Memory Virtualization

## 1. Definition

Memory Virtualization is the process of creating virtual memory for each virtual machine (VM). It allows multiple VMs to share the physical memory (RAM) of a host computer while making each VM believe it has its own dedicated memory.

## 2. Simple Definition for Exams

Memory virtualization is the technique of dividing and managing physical memory (RAM) among multiple virtual machines using a hypervisor.

## 3. How Memory Virtualization Works

1. The physical server contains RAM (physical memory).
    
2. The hypervisor divides the physical memory into virtual memory for each VM.
    
3. Each VM is allocated a specific amount of memory.
    
4. The hypervisor manages and maps virtual memory to physical memory.
    
5. Every VM behaves as if it has its own dedicated memory.
    

## 4. Advantages of Memory Virtualization

- **Better utilization of RAM:** Physical memory is used efficiently.
    
- **Multiple VMs:** Several virtual machines can run simultaneously.
    
- **Memory sharing and dynamic allocation:** Memory can be managed according to requirements.
    
- **Reduced hardware costs:** Multiple VMs can share the same physical memory resources.
    

## 5. Example

Suppose a physical server has 16 GB of RAM. The hypervisor allocates 4 GB of virtual memory to VM1 and 6 GB to VM2, while managing the server's available physical memory for the virtual machines.

## 6. Simple Diagram

Physical RAM  
↓  
Hypervisor  
↓  
Virtual Memory for Each VM  
↓  
VM1  VM2  VM3

## 7. Summary

Memory virtualization allows multiple virtual machines to share a host computer's physical RAM. The hypervisor allocates and manages memory resources for each VM efficiently.

[[09 - Input Output Virtualization]]
