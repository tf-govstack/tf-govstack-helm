# keygen

Helm chart for installing Kernel module keygen.

## TL;DR

```console
$ helm repo add tf-govstack  https://tf-govstack.github.io
$ helm install my-release tf-govstack/keygen
```

## Introduction

The helm chart here essentially contains job that generates encryption keys for kernel modules.  The job is to be run only once during initial install.

## Prerequisites

- Kubernetes 1.12+
- Helm 3.1.0
- PV provisioner support in the underlying infrastructure
- ReadWriteMany volumes for deployment scaling

## Installing the Chart

To install the chart with the release name `keygen`.

```console
helm install my-release tf-govstack/keygen
```

The command deploys keygen on the Kubernetes cluster in the default configuration. The [Parameters](#parameters) section lists the parameters that can be configured during installation.

> **Tip**: List all releases using `helm list`

## Uninstalling the Chart

To uninstall/delete the `my-release` deployment:

```console
helm delete my-release
```
The command removes all the Kubernetes components associated with the chart and deletes the release.

