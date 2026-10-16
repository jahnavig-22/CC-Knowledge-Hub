# CPU Virtualization

## 1. Definition

CPU Virtualization is the process of creating virtual CPUs (vCPUs) from a single physical CPU. It allows multiple virtual machines (VMs) to share the same processor, with each VM behaving as if it has its own dedicated CPU.

## 2. Simple Definition for Exams

CPU virtualization is the technique of dividing a physical CPU into multiple virtual CPUs (vCPUs), allowing multiple virtual machines to share the same processor efficiently.

## 3. How CPU Virtualization Works

1. A physical computer has one or more physical CPUs.
    
2. The hypervisor creates one or more virtual CPUs (vCPUs).
    
3. Each virtual machine is assigned one or more vCPUs.
    
4. The hypervisor schedules CPU time among all virtual machines.
    
5. Every VM behaves as if it has its own CPU, even though the virtual machines share the physical processor.
    

## 4. Advantages of CPU Virtualization

- **Better CPU utilization:** Uses processor resources efficiently.
    
- **Supports multiple operating systems:** Different VMs can run different operating systems.
    
- **Reduces hardware cost:** Multiple VMs can share one physical computer.
    
- **Improves flexibility and scalability:** CPU resources can be allocated according to requirements.
    

## 5. Example

Suppose a physical server has one CPU and runs three virtual machines: VM1, VM2, and VM3. The hypervisor assigns virtual CPUs to these VMs and schedules their use of the physical processor.

Each VM behaves as if it has its own CPU, although the physical processing resources are shared.

## 6. Simple Diagram

Physical CPU  
↓  
Hypervisor  
↓  
Virtual CPUs (vCPUs)  
↓  
VM1  VM2  VM3

## 7. Summary

CPU virtualization creates virtual CPUs from physical processor resources. The hypervisor assigns vCPUs to virtual machines and schedules CPU time so that multiple VMs can share the physical processor efficiently.

[[08 - Memory Virtualization]]
