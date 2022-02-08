# IaC-at-home
Documentation and configuration for my attempt to bootstrap and maintain my 
home cluster from a github repo.

This is to be a bare metal cluster and the goal is to bootstrap everything 
including the base OS on each node.

This is the next stage in my K8s journey with K3s. The previous work
is documented here https://github.com/gilesknap/k3s-minecraft

## Hardware
- 3 * Raspberry Pi 4 with 4GB RAM +32GB USB3 flash
- 1 * Raspberry Pi 8 with 8GB RAM +32GB USB3 flash
- 1 Intel NUC I7 with 32GB RAM +250GB Nvme + 4TB SSD for backup
- 1 QNAP TS-x53D NAS with RAID 1 pair of SSD 4TB
- 1 Workstation AMD Ryzen 78500X 32 GB RAM Nvidia RX 3090 GPU

The NAS will provide storage and any 'outside of the cluster' services needed for bootstrapping/management. This repo will hold instructions and config files for bootstrapping the NAS. All NAS services will run inside the QNAP Container Station.

# Steps 
- [Install dnsmasq on the NAS](nas/dnsmasq/README.md)
- TBA ...
- ...
