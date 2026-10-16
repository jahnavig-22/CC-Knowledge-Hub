# Para Virtualization

## 1. Definition

Para virtualization is a virtualization technique in which the guest operating system is modified to work with the hypervisor. The guest OS is aware that it is running in a virtualized environment.

## 2. How Para Virtualization Works

1. The guest operating system is modified to support virtualization.
    
2. The guest OS communicates with the hypervisor using **hypercalls**.
    
3. The hypervisor manages access to physical hardware resources.
    
4. This approach reduces the need to emulate complete hardware.
    

## 3. Features of Para Virtualization

- The guest operating system is modified.
    
- The guest OS is aware of virtualization.
    
- It uses hypercalls to communicate with the hypervisor.
    
- It reduces hardware emulation.
    
- It can improve performance.
    

## 4. Example

**Xen** is an example associated with para virtualization.

## 5. Advantages

- Can provide better performance by reducing emulation overhead.
    
- Allows efficient communication between the guest OS and hypervisor.
    

## 6. Limitations

- The guest operating system may need modification.
    
- Unmodified operating systems may not be supported by this approach.
    

## 7. Full Virtualization vs Para Virtualization

|Full Virtualization|Para Virtualization|
|---|---|
|Guest OS does not need modification.|Guest OS needs modification.|
|Guest OS is unaware of virtualization.|Guest OS is aware of virtualization.|
|Provides a complete virtual hardware environment.|Uses hypercalls to communicate with the hypervisor.|
|Example: VMware ESXi, Microsoft Hyper-V.|Example: Xen.|

## 8. Summary

Para virtualization is a technique in which the guest operating system is modified to communicate with the hypervisor through hypercalls. It reduces hardware emulation and can improve performance.

[[06 - Hardware Virtualization]]
