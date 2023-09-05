# Group 4 Stage

Helm chart for installing Registration Processor Group 4 stage.

## Install
```console
$ kubectl create namespace regproc
$ helm repo add tf-govstack  https://tf-govstack.github.io
$ helm -n regproc install my-release mosip/regproc-group4
```

