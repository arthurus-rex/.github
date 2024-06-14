## Hi there 👋


# 🙋‍♀️ A short introduction

- Kepler (Kubernetes-based Efficient Power Level Exporter) uses eBPF to probe energy related system stats and exports as Prometheus metrics 
- PEAKS (Power Efficiency Aware Kubernetes Scheduler) uses metrics exported by Kepler to help Kubernetes schedule to improve energy efficiency by placing Pods on optimal nodes.
- CLEVER (Container Level Energy-efficient VPA Recommender) uses metrics exported by Kepler to recommend Vertical Pod Autoscaler the resource profiles to improve energy efficiency by running workloads.

# 🧭 Navigating the repositories

## Kepler
See the [online docs](https://sustainable-computing.io/), or you can build from source [here]( https://github.com/sustainable-computing-io/kepler/blob/main/CONTRIBUTING.md).

### [kepler](https://github.com/sustainable-computing-io/kepler)
Main Kepler repository.
Kepler uses [eBPF](https://sustainable-computing.io/design/ebpf_in_kepler/) to export energy-related system stats as [Prometheus metrics](https://sustainable-computing.io/design/metrics/), and can be deployed by either building directy with Manifests (docs [here](https://sustainable-computing.io/installation/kepler/)) or with Helm Chart (docs [here](https://sustainable-computing.io/installation/kepler-helm/), repo [here](https://github.com/sustainable-computing-io/kepler-helm-chart/tree/main).
It can also be installed as [RPM](https://sustainable-computing.io/installation/kepler-rpm/).
For developers, we also have a [contribution guide](https://github.com/sustainable-computing-io/kepler/blob/main/CONTRIBUTING.md).

### [kepler-operator](https://github.com/sustainable-computing-io/kepler-operator)
Installs Kepler and all required manifests on Kubernetes/OpenShift.  This requires either a Kind or MicroShift local cluster for testing, or to be run against a remote cluster.
Can be installed as a community operator on OpenShift ([docs](https://sustainable-computing.io/installation/community-operator/)) or against a Kind cluster ([docs](https://sustainable-computing.io/installation/kepler-operator/)).
For contributers, developer docs can be found [here](https://github.com/sustainable-computing-io/kepler-operator/tree/v1alpha1/docs/developer).

## Kepler Energy Models
## [kepler-model-server](https://github.com/sustainable-computing-io/kepler-model-server)
## [kepler-model-db](https://github.com/sustainable-computing-io/kepler-model-db)
## [kepler-model-training-playbook](https://github.com/sustainable-computing-io/kepler-model-training-playbook)

## Kepler Helpers
### [kepler-helm-chart](https://github.com/sustainable-computing-io/kepler-helm-chart/tree/main)

## For Developers
## [kepler-action](https://github.com/sustainable-computing-io/kepler-action)
## [kepler-metal-ci](https://github.com/sustainable-computing-io/kepler-metal-ci)

## Archived
### [kepler-ci-artifacts](https://github.com/sustainable-computing-io/kepler-ci-artifacts)
### [kepler-estimator](https://github.com/sustainable-computing-io/kepler-estimator)
### [kepler-operator-java](https://github.com/sustainable-computing-io/kepler-operator-java)


# 🌏🌲🌳 Contribution guidelines - how can the community get involved?

We use [CNCF Code of Conduct](https://github.com/cncf/foundation/blob/main/code-of-conduct.md)
# 👩‍💻 Useful resources 
 Slack: 
 https://sustainableco-ese6814.slack.com/archives/C02VCJ8K8LT
 
 Doc:
 https://github.com/sustainable-computing-io/kepler-doc
# 🍿 Fun facts 
Kepler project aims to help curb Kubernetes energy waste 
https://www.techtarget.com/searchitoperations/feature/How-to-approach-sustainability-in-IT-operations

Want to learn more?  [Kepler in the news!]

