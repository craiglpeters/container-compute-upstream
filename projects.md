# Container Compute Upstream Projects

> Note: This content may be moved to the README.md when ready.

This list of projects is maintained by the upstream team. The goals of this list are to make it easy to:

* Find projects and maintainers
* Make informed decisions about what projects to use
* Learn how to contribute to the projects

## Maturity

Some of the items listed below are full-fledged open source projects, while others are subprojects or contribution areas.

* Each open source project is evaluated against a maturity model. Those currently in Azure, Microsoft, or deislabs GitHub orgs use the maturity model defined in the [guaduation guidelines](process/graduation_guidelines.md). Those in CNCF uses their [maturity model](https://github.com/cncf/toc/blob/master/process/graduation_criteria.adoc).
* Each subproject or contibution Maturity references the stability of the API it provides.

> TODO: Update with Microsoft open source support statement...

> TODO: Should the table include a Microsoft contact, or email alias, for each project?

## Project list

| Project Area | Project | Goal | Maturity | Communication |
|---|---|---|---|---|
| Kubernetes Cluster Management |  |  |  |  |
|  | [AKS Engine](https://github.com/Azure/aks-engine) | Self-managed clusters on Azure | Azure: incubating | [#aks-engine-users](https://kubernetes.slack.com/archives/CU3N85WJK) <br> [GitHub issues](https://github.com/Azure/aks-engine/issues) |
|  | [Cluster API Azure Provider](https://sigs.k8s.io/cluster-api-provider-azure) | Self-managed clusters on Azure using Cluster API | CNCF: incubating | [#cluster-api-azure](https://kubernetes.slack.com/archives/CEX9HENG7) <br> [kubernetes-sig-cluster-lifecycle@googlegroups.com](https://groups.google.com/forum/#!forum/kubernetes-sig-cluster-lifecycle) <br> [GitHub issues](https://github.com/kubernetes-sigs/cluster-api-provider-azure/issues) |
| Kubernetes Azure Cloud Provider |  |  |  |  |
|  | [In-tree (legacy)](https://github.com/kubernetes/kubernetes/tree/master/staging/src/k8s.io/legacy-cloud-providers/azure) | Use Azure infra for K8s | CNCF: graduated | [#provider-azure](https://kubernetes.slack.com/archives/C5HJXTT9Q) <br> [kubernetes-provider-azure@googlegroups.com](https://groups.google.com/forum/#!forum/kubernetes-provider-azure) <br> [GitHub issues](https://github.com/kubernetes/kubernetes/issues?q=is%3Aissue+is%3Aopen+label%3Aarea%2Fprovider%2Fazure+) |
|   | [Out-of-tree (new)](https://sigs.k8s.io/cloud-provider-azure) | Use Azure infra for K8s | CNCF: ?? | same slack and email <br> [GitHub issues](https://github.com/kubernetes-sigs/cloud-provider-azure/issues) |
|   | [Azure Disk CSI Driver](https://sigs.k8s.io/azuredisk-csi-driver) | Enable use of Azure disk volume | CNCF: ?? | same slack and email <br> [GitHub issues](https://github.com/kubernetes-sigs/azuredisk-csi-driver/issues)  |
|   | [Azure File CSI Driver](https://sigs.k8s.io/azurefile-csi-driver) | Enable use of Azure disk volume | CNCF: ?? | same slack and email <br> [GitHub issues](https://sigs.k8s.io/azurefile-csi-driver/issues) |
|   | [Azure Blobfuse CSI Driver](https://sigs.k8s.io/blobfuse-csi-driver) | Enable use of [azure-storage-fuse](https://github.com/Azure/azure-storage-fuse) | CNCF: ?? | same slack and email <br> [GitHub issues](https://github.com/kubernetes-sigs/blobfuse-csi-driver/issues) |
| Container Runtimes |  |  |  |  |
|  | [Moby](https://github.com/moby/moby) | Toolkit for app containerization | Moby: ?? | [#opencontainers](https://opencontainers.slack.com/archives/C0LQVA03W) |
|  | Containerd |  | Containerd: ?? |  |  |
| Kubernetes Enhancements |  |  |  |  |
|  | Virtual Kubelet |  |  |  |
|  | Windows containers |  |  |  |
|  | IP v4/v6 Dual Stack |  |  |  |
| Cloud Native Governance and Security |  |  |  |  |
|  | AAD Pod Identity |  |  |  |
|  | OPA Gatekeeper |  |  |  |
|  | Flexvol Keyvault |  |  |  |
|  | Secrets Store CSI Driver |  |  |  |
| Cloud Native Service Mesh |  |  |  |  |
|  | Service Mesh Interface (SMI) |  |  |  |
|  |  |  |  |  |
