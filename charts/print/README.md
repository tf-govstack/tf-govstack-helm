# Print Service

Helm chart for installing sample Print service module. This is a reference implementation that needs to be customized by a country.

## Install

```console
$ helm repo add tf-govstack  https://tf-govstack.github.io
$ helm install my-release tf-govstack/print-service
```
## Prerequisites

- Kubernetes 1.12+
- Helm 3.1.0
- PV provisioner support in the underlying infrastructure
- ReadWriteMany volumes for deployment scaling

