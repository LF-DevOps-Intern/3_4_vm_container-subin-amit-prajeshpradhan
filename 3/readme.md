# Question 3

> What problem does Virtualization solves and what is its drawback in context to modern application deployments?


Problem that Virtualization solves:
- VMs provide isolated environments, making it possible to run different types of OSes and applications on a single server. Organizations can deploy legacy and business applications in the environments they require, without having to deal with contention issues or needing to purchase multiple servers to support different environments.
- VMs make it easy to scale applications and accommodate fluctuating workloads, which is one reason virtualization plays such a key role in cloud computing.
- Organizations also turn to VMs because of the extra layer of security they provide against potential threats. If a VM is compromised, it can be deleted or rolled back to a recent backup or snapshot. Because it's isolated from the host and other VMs, the threat is limited to that VM.
  
Drawback of Virtualization:
- **Ineffective resource usage**
Once a VM is assigned to a resource, it takes up the whole space, even when it needs less. This creates idle power that you can use elsewhere if your planning is inaccurate.
- **Not as portable**
Virtual machines are gigabytes-sized chunks of software. The applications run on a virtual machine that is highly dependent on the OS and the emulated hardware it runs on.
