---
title: Taxonomies
---

# Taxonomies

1. Taxonomies
  1. VM
  2. Client-Server
  3. Exokernel
  4. MicroKernel

##  VM 

> As tanenbaum says in Modern Operating Systems. Another use of virtualization is for end users who want to be able to run two or more operating systems at the same time, say Windows and Linux, because some of their favorite application packages run on one and some run on the other. ..., where the term "virtual machine monitor" has been renamed type 1 hypervisor,

### Whats the difference between type 1 hypervisor and type 2 hypervisor
{{< lead >}}
  In practice the real distinction is that type 2 makes uses of a **host operating system** and its file system to create processes, store files, and so on. A type 1, has no underlaying support and must perform all these actions itself
  
  After type 2 hypervisor is started, it reads the CD-ROM image file for the choosen **guest operating system**, and installs it on a virtual disk, which is just a simple big file in the host operating system's file system.
  Type 1 hypervisor cannot do this because there is no host operating system to store files on. They must live and manage them in its own raw disk partition.
{{< /lead >}}

+ whats the difference between virtual machine monitor and virtual machine

{{< lead >}}
A different approach to **handling control instructions** is to modify the operating system to remove them. This approach is not true virtualization, but paravirtual-ization.
{{< /lead >}}

{{< alert >}}
In order to run virtual machine software on a computer, its CPU must be virtualizable (Popek and Goldberg, 1974)
{{< /alert >}}

Several advantages:

1. binary translation
  Translating blocks of code on the fly, storing them in a internal cache, reusing them if they were executed again. Lead to what we call machine simulators. (this was not enough fast)
2. kernel module
  Does some of the heavy lifting. With this and many other more improvements the virtual machine monitor are called type 2 hypervisors

### Java Virtual Machine

JVM (i.e., a computer arquitecture), the java compiler `javac` produces code for the JVM, which then is executed by a software JVM interpreter.

## Exokernels

At the bottom layer, running in kernel mode there is a program called exokernel. Its job is to allocate resources to virtual machines and then check attemps to use them to make sure no machine is trying to use somebody else's resources. Each user-level VM can run its own OS. But it's restricted to only use the resources it has asked for and been allocated.

NOTE: esto es lo que dijo JJ, sobre la diferencia entre virtualización (VM) y contenerización. VM existe un hypervisor y administra recursos, el exokernel se asegura que los recursos no sean invadidos

This scheme saves a layer of mapping (memory addresses). The virtual machine monitor must mantain tables to remap disk addresses (and all other resources). With exokernel this mapping is not needed. Since all the exokernel has to do is keep the vm's out of each other's hair.
