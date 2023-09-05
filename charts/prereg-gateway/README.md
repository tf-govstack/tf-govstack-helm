# PreReg Istio Gateway

Helm chart for installing Pre-Registration Istio gateway

## Install
```console
$ kubectl create namespace prereg
$ helm repo add tf-govstack  https://tf-govstack.github.io
$ helm -n prereg install my-release mosip/prereg-gateway
```

