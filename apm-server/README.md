
## Requirements

* Kubernetes >= 1.9
* [Helm][] >= 2.8.0

## Installing

### Install released version using Helm repository

* Add the Elastic Helm charts repo:
`helm repo add elastic https://helm.elastic.co`

* Install it:
  - with Helm 2: `helm install --name apm-server elastic/apm-server`
  - with [Helm 3 (beta)][]: `helm install apm-server elastic/apm-server`
