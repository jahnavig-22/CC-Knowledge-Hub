# Input/Output (I/O) Virtualization

## 1. Definition

Input/Output (I/O) Virtualization is the process of allowing multiple virtual machines (VMs) to share physical input and output devices, such as disks, keyboards, mice, printers, network cards, and USB devices, through the hypervisor.

## 2. Simple Definition for Exams

I/O virtualization is the technique of sharing physical input and output devices among multiple virtual machines using a hypervisor.

## 3. How I/O Virtualization Works

1. The physical computer contains I/O devices such as storage disks, network adapters, printers, and USB devices.
    
2. The hypervisor creates virtual I/O devices for each VM.
    
3. Each VM accesses these virtual devices as if they were real hardware.
    
4. The hypervisor manages communication between the VMs and the physical devices.
    

## 4. Advantages of I/O Virtualization

- **Reduces hardware requirements:** Multiple VMs can share physical devices.
    
- **Improves resource utilization:** Devices are used more efficiently.
    
- **Simplifies device management:** The hypervisor manages access to physical devices.
    
- **Supports resource sharing:** Multiple VMs can use the same network and storage devices.
    

## 5. Example

A physical server has one network card and one storage disk. The hypervisor provides virtual network and storage devices so that VM1, VM2, and VM3 can access these resources.

## 6. Simple Diagram

Physical I/O Devices  
(Network Card, Storage Disk, USB Devices)  
↓  
Hypervisor  
↓  
Virtual I/O Devices  
↓  
VM1  VM2  VM3

## 7. Summary

I/O virtualization allows multiple virtual machines to share physical input and output devices through a hypervisor. It improves device utilization and simplifies resource management.

[[10 - Virtualization Basics]]
