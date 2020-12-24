# Results
I have done some operations with virtual machines using virtualbox and vagrant. Vagrant allows us to do with virtual machines all the same as virtualbox, and even expands its functionality. It is not replaceable if we need a quick deployment of a large number of preconfigured virtual machines.

## Part 1
### What are the most popular hypervisors for infrastructure virtualization?
VMware vSphere Hypervisor, Microsoft Hyper-V, Oracle VirtualBox, KVM, Qemu.
### Briefly describe the main differences of the most popular hypervisors.
Hyper-V is a type 1 hypervisor developed by Microsoft and is only available on the Windows platform. VMware vSphere Hypervisor is a type 2 hypervisor that is available for all platforms and is mainly used in commercial projects. Virtualbox is a type 2 hypervisor that is freely distributed and used primarily on home hosts. Qemu is mainly used in conjunction with KVM, which is built into the Linux kernel. This is the native Linux virtualization method with the best hardware performance.

## Part 2
### Creating, cloning, and grouping virtual machines.
![Sreenshot](/m2/task2.1/screenshots/Picture1.jpg)

![Sreenshot](/m2/task2.1/screenshots/Picture2.jpg)

![Sreenshot](/m2/task2.1/screenshots/Picture3.jpg)

### Exporting VM
![Sreenshot](/m2/task2.1/screenshots/Picture4.jpg)

![Sreenshot](/m2/task2.1/screenshots/Picture5.jpg)

### Possible connections table
| Mode       | VM->Host | VM<-Host     | VM1<->VM2 | VM->Net/LAN | VM<-Net/LAN  |
|------------|----------|--------------|-----------|-------------|--------------|
| Host-only  | +        | +            | +         | -           | -            |
| Internal   | -        | -            | +         | -           | -            |
| Bridged    | +        | +            | +         | +           | +            |
| NAT        | +        | Port forward | -         | +           | Port forward |
| NATservice | +        | Port forward | +         | +           | Port forward |

### Working with CLI through VBoxManage
The vboxmanage utility comes with virtualbox. It allows us to work with virtual machines through the command line: launch them, create, clone, modify, take a snapshot, display various information and much more. Some commands extend the possibilities of managing virtual machines of the GUI version of virtualbox. For example, using the modifyvm command, we can resize the disk of an existing virtual machine.

## Part 3
### Initializing and starting vagrant box
![Sreenshot](/m2/task2.1/screenshots/Picture6.jpg)

![Sreenshot](/m2/task2.1/screenshots/Picture7.jpg)

### Connecting to VM via ssh
There are 2 easy ways to do this. The first one is to connect using the open-ssh utility. The second of them is even simpler - connect using the vagrant ssh command.

![Sreenshot](/m2/task2.1/screenshots/Picture8.jpg)

![Sreenshot](/m2/task2.1/screenshots/Picture9.jpg)

### Stoping and removing vagrant box
![Sreenshot](/m2/task2.1/screenshots/Picture10.jpg)

![Sreenshot](/m2/task2.1/screenshots/Picture11.jpg)

### Creating own vagrant box
![Sreenshot](/m2/task2.1/screenshots/Picture12.jpg)
