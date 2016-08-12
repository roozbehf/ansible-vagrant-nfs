# Simple NFS Server on Vagrant

This is the Vagrant configuration of a simple NFS server based on CentOS 7.

## Networking
The machine is configured with a bridge network. At the time of creation you may need to identify a host interface to be used as the bridge interface.

## Shared Folder
The folder shared over the network is `/var/nfsshare`.
