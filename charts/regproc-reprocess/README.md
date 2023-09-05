# Packet Reprocess

Helm chart for installing Registration Processor Reprocess stage.

## Install
```console
$ kubectl create namespace regproc
$ helm repo add tf-govstack  https://tf-govstack.github.io
$ helm -n regproc install my-release mosip/regproc-reprocess
```

