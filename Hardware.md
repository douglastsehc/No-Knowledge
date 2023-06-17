# Hardware
## Bare Metal
Once upon a time, all bare metal only
<Br>
Physical computer is a single tenant only


Bare Metal Computer complete control of the resources including hardware resources
and software to run
### Advantage
Can have absolute higher performance from the hardware.

Without affect by any noisy neighbor problem
no share of other tenant sharing same hardware

Isolations provide highest security
Not affect by side channel attack
    no design flaws in modern microrpocessors to allow a malicious tenant to steal secrets from neighbour
### Disadvantage
Bare Metal is expensive hard to manage and hard to scale
## Virtual Machines (Virtualization)
Emulation for a physical computer 
Use hypervisor
Hypervisor manage virtual machines, create abstraction layer over the hardware

Bare metal hypervisor control the hardware directly without host operating system
### Advantage
Cheaper to run, share same hardware allowing much higher resource utilization, easier to scale, more flexibility 
### Disadvantage
Vulnerable for noisy neighbor problem
share same physical cpu cost.
side channel attack like meltdown and  spectre

## Containers
Lightweigth and standalone package of an application for all dependenices
Containerization.

Container engine run many containers,

faster resource provisioning, package resource together 

### Advantage
Scalable and portalbe, lightweight and require less hardware resources
### Disadvantage
less secure, share same OS and the isolation relies on OS-level primitives

## Serverless

## Edge-computing
