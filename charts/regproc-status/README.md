# Regproc Status Service

Helm chart for installing Reg Proc Status Service.

## TL;DR

```console
$ helm repo add tf-govstack  https://tf-govstack.github.io
$ helm install my-release tf-govstack/regproc-status
```
## Prerequisites

- Kubernetes 1.12+
- Helm 3.1.0
- PV provisioner support in the underlying infrastructure
- ReadWriteMany volumes for deployment scaling

