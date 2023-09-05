# PreReg Captcha Service

Helm chart for installing Pre-Registration Captcha Service

## Install
```console
$ kubectl create namespace prereg
$ helm repo add tf-govstack  https://tf-govstack.github.io
$ helm -n prereg install my-release mosip/prereg-captcha
```

