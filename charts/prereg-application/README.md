# PreReg Application

Helm chart for installing Pre-Registration Application service.

## Install
```console
$ kubectl create namespace prereg
$ helm repo add tf-govstack  https://tf-govstack.github.io
$ helm -n prereg install my-release mosip/prereg-application
```

