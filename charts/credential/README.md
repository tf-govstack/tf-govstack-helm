# IDRepo Credential Service

Helm chart for installing IDrepo Credential service. 

## TL;DR

```console
$ helm repo add tf-govstack  https://tf-govstack.github.io
$ helm -n idrepo install my-release mosip/credential
```
## Prerequisites

- Kubernetes 1.12+
- Helm 3.1.0
- PV provisioner support in the underlying infrastructure
- ReadWriteMany volumes for deployment scaling

