# Cameron's Homelab Ansible

This is a self-centered project to manage infrastructure I have within my homelab.

Current hardware managed:

- Raspberry Pi cluster (3 nodes)
    1. _kube-master01_ (K3s master node)
        - Raspberry Pi 4B+ w/ 128 GB SD Card
    2. _kube-worker02_ (K3s worker node)
        - Raspberry Pi 4B+ w/ 64 GB SD Card
    3. _kube-worker03_ (K3s worker node)
        - Raspberry Pi 4B+ w/ 64 GB SD Card

## Roles
_for information on how the roles work, see the role's readme.md file._
1. docker
