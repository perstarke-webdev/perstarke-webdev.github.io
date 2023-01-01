---
name: "Enable ssh access to multipass vms"
tag: vms
author: Gernot Starke
paper: dev.to
link: https://dev.to/arc42/enable-ssh-access-to-multipass-vms-36p7
---
The problem:
You are using multipass to create lightweight virtual (Ubuntu) machines.
You want to `ssh` into those machines, because you cannot or don't want to use the standard shell command `multipass shell
< name-of-vm >`.

The naive approach fails with permission denied - Permission denied, although there is a route to this virtual machine available...