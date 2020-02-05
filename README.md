# okd-github-actions-demo

## Install oc binary

- https://github.com/openshift/origin/releases/download/v3.11.0/openshift-origin-client-tools-v3.11.0-0cbc58b-linux-64bit.tar.gz

- https://github.com/openshift/origin/releases/tag/v3.11.0

## OpenShift 3.11 cluster

```
oc cluster up --skip-registry-check=true
```

## Common Issues

- [oc cluster up does not recognize --insecure-registry argument](https://github.com/openshift/origin/issues/8997)
