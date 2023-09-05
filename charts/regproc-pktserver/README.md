# Packet server 

Helm chart for installing RegProc Packet Server.  This serves packets from landing folder to other stages.

## TL;DR

```console
$ helm repo add tf-govstack  https://tf-govstack.github.io
$ helm install my-release tf-govstack/regproc-pktserver
```
## Persistence
It is assumed PVC created in Receiver is available to be mounted here.

## Prerequisites
- Kubernetes 1.12+
- Helm 3.1.0
- PV provisioner support in the underlying infrastructure
- ReadWriteMany volumes for deployment scaling

