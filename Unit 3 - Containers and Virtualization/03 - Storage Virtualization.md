# Storage Virtualization

## 1. Definition

Storage virtualization is a technology that combines multiple physical storage devices, such as hard drives and SSDs, into a single virtual storage pool.

This pool appears to users or applications as one large storage system.

## 2. How Storage Virtualization Works

1. Multiple physical storage devices are connected to a storage system.
    
2. Virtualization combines their storage capacity into a virtual storage pool.
    
3. The storage system manages the physical storage resources.
    
4. Users and applications access the storage through the virtual system.
    

## 3. Types of Storage Virtualization

### 1. Block-Level Virtualization

- Divides physical storage into blocks and combines them into a virtual storage unit.
    
- Each block can be managed, moved, or copied independently.
    
- Improves flexibility and storage management.
    
- Commonly used in Storage Area Networks (SANs).
    
- **Example:** Presenting storage from multiple physical devices as one large virtual disk.
    

### 2. File-Level Virtualization

- Combines files from different storage devices and presents them through a single shared folder or file system.
    
- Makes it easier for users to access files stored across multiple devices.
    
- Commonly associated with Network-Attached Storage (NAS) systems.
    
- **Example:** Employees accessing shared company documents through one network folder.
    

## 4. Important Terms

**Storage Area Network (SAN):** A network that provides servers with access to shared storage, commonly at the block level.

**Network-Attached Storage (NAS):** A storage device connected to a network that allows multiple users to access shared files.

## 5. Advantages

1. Combines storage resources into a shared pool.
    
2. Makes storage management easier.
    
3. Improves flexibility in allocating storage.
    
4. Allows users to access shared files more conveniently.
    
5. Can improve the utilization of available storage capacity.
    

## 6. Real-Life Example

A company has several hard drives and SSDs containing employee documents. Storage virtualization combines their capacity into a shared storage pool, making it easier for the company to manage and allocate storage.

## 7. Summary

Storage virtualization combines physical storage resources into a virtual storage system. Block-level virtualization works with storage blocks, while file-level virtualization provides access to files through a unified file system or shared folder.

[[04 - Operating System Level Virtualization]]
