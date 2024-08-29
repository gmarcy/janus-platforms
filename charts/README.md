# Helm Charts

This folder contains helm charts that can be used to setup supporting applications used by the rhdh platform.

## Installing components using helm

```bash
helm install $NAME -f my-values.yaml charts/$CHART_NAME
eg:
helm install my-gitops -f my-values.yaml charts/gitops-operator
```

## Chart README Files
For more info on each chart checkout these!
* [gitops-operator](/charts/gitops-operator)
* [pipelines-operator](/charts/pipelines-operator)
* [rhdh-backstage](/charts/rhdh-backstage)
* [rhsso-backstage](/charts/rhsso-backstage)
* [rhsso-cluster-auth](/charts/rhsso-cluster-auth)