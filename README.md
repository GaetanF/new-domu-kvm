# new-domu-kvm
Script to create Virtual Machines using debootstrap under KVM.

This script will format a disk (presented by iSCSI or FC or LOCAL) with LVM.
After this script install the system using debootstrap.
And install the boatloader on the disk to be ready to use for KVM

The virtual machine can be started using Libvirt or using directly KVM.
