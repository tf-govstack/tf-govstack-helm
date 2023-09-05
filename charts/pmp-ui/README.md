# PMP-UI

Helm chart for installing MOSIP PMP UI module

## TL;DR

```console
$ helm repo add tf-govstack  https://tf-govstack.github.io
$ helm install my-release tf-govstack/pmp-ui
```

## Prerequisites

- Kubernetes 1.12+
- Helm 3.1.0
- PV provisioner support in the underlying infrastructure
- ReadWriteMany volumes for deployment scaling

## Installing the Chart

To install the chart with the release name `pmp-ui`.

```console
helm install my-release tf-govstack/pmp-ui
```

> **Tip**: List all releases using `helm list`

## Uninstalling the Chart

To uninstall/delete the `my-release` deployment:
