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

## Support

These are open source projects that Microsoft maintain or contribute to. They are [**not** covered by the Microsoft Azure support policy](https://support.microsoft.com/en-us/help/2941892/support-for-linux-and-open-source-technology-in-azure). In general, please search open issues, and if your issue isn't already represented please open a new one. The project maintainers will respond to the best of their abilities.

> TODO: Should the table include a Microsoft contact, or email alias, for each project?

> TODO: How to suggest a new project

## Project list

| Project Area | Project | Goal | Maturity | Communication |
|---|---|---|---|---|
| Kubernetes Cluster Management |  |  |  |  |
|  | [AKS Engine](https://github.com/Azure/aks-engine) | Self-managed clusters on Azure | Azure: incubating | [#aks-engine-users](https://kubernetes.slack.com/archives/CU3N85WJK) <br> [GitHub issues](https://github.com/Azure/aks-engine/issues) |
|  | [Cluster API Azure Provider](https://sigs.k8s.io/cluster-api-provider-azure) | Self-managed clusters on Azure using Cluster API | CNCF: incubating | [#cluster-api-azure](https://kubernetes.slack.com/archives/CEX9HENG7) <br> [kubernetes-sig-cluster-lifecycle@googlegroups.com](https://groups.google.com/forum/#!forum/kubernetes-sig-cluster-lifecycle) <br> [GitHub issues](https://github.com/kubernetes-sigs/cluster-api-provider-azure/issues) |
| Kubernetes Azure Cloud Provider |  |  |  |  |
|  | [In-tree (legacy)](https://github.com/kubernetes/kubernetes/tree/master/staging/src/k8s.io/legacy-cloud-providers/azure) | Use Azure infra for K8s | CNCF: graduated | [#provider-azure](https://kubernetes.slack.com/archives/C5HJXTT9Q) <br> [kubernetes-provider-azure@googlegroups.com](https://groups.google.com/forum/#!forum/kubernetes-provider-azure) <br> [GitHub issues](https://github.com/kubernetes/kubernetes/issues?q=is%3Aissue+is%3Aopen+label%3Aarea%2Fprovider%2Fazure+) |
|   | [Out-of-tree (new)](https://sigs.k8s.io/cloud-provider-azure) | Use Azure infra for K8s | CNCF: alpha | same slack and email <br> [GitHub issues](https://github.com/kubernetes-sigs/cloud-provider-azure/issues) |
|   | [Azure Disk CSI Driver](https://sigs.k8s.io/azuredisk-csi-driver) | Enable use of Azure disk volume | CNCF: ?? | same slack and email <br> [GitHub issues](https://github.com/kubernetes-sigs/azuredisk-csi-driver/issues)  |
|   | [Azure File CSI Driver](https://sigs.k8s.io/azurefile-csi-driver) | Enable use of Azure disk volume | CNCF: ?? | same slack and email <br> [GitHub issues](https://sigs.k8s.io/azurefile-csi-driver/issues) |
|   | [Azure Blobfuse CSI Driver](https://sigs.k8s.io/blobfuse-csi-driver) | Enable use of [azure-storage-fuse](https://github.com/Azure/azure-storage-fuse) | CNCF: ?? | same slack and email <br> [GitHub issues](https://github.com/kubernetes-sigs/blobfuse-csi-driver/issues) |
| Container Runtime |  |  |  |  |
|  | [Moby](https://github.com/moby/moby) | Toolkit for app containerization | Moby: ?? | [#opencontainers](https://opencontainers.slack.com/archives/C0LQVA03W) <br> [Moby Forums](https://forums.mobyproject.org/) <br> [GitHub issues](https://github.com/moby/moby/issues) |
|  | [Containerd](https://github.com/containerd/containerd) | Complete container lifecycle management on Linux and Windows hosts | CNCF: graduated | [#opencontainers](https://opencontainers.slack.com/archives/C0LQVA03W) <br> [dev@opencontainers.org](https://groups.google.com/a/opencontainers.org/forum/#!forum/dev) <br> [GitHub issues](https://github.com/containerd/containerd/issues) |
| Kubernetes Enhancements |  |  |  |  |
|  | [Virtual Kubelet](https://github.com/virtual-kubelet/virtual-kubelet/) | Enable services to masquerade as kubelet - serverless | CNCF: sandbox | [#virtual-kubelet](https://kubernetes.slack.com/archives/C8YU1QP8W) <br> [GitHub issues](https://github.com/virtual-kubelet/virtual-kubelet/issues) |
|  | [Windows containers](https://kubernetes.io/docs/setup/production-environment/windows/intro-windows-in-kubernetes/) | Run Windows server containers with Kubernetes | K8s API: stable | [#sig-windows](https://kubernetes.slack.com/archives/C0SJ4AFB7) <br> [kubernetes-sig-windows@googlegroups.com](https://groups.google.com/forum/#!forum/kubernetes-sig-windows) <br> [Windows Community Forum](https://discuss.kubernetes.io/c/general-discussions/windows) <br> [GitHub issues](https://github.com/kubernetes/kubernetes/issues?q=is%3Aissue+is%3Aopen+label%3Asig%2Fwindows+) |
|  | [IPv4/v6 Dual Stack](https://kubernetes.io/docs/concepts/services-networking/dual-stack/) | IPv4/IPv6 dual-stack enables the allocation of both IPv4 and IPv6 addresses to Pods and Services. | K8s API: alpha | [#sig-network](https://kubernetes.slack.com/archives/C09QYUH5W) <br> [kubernetes-sig-network@googlegroups.com](https://groups.google.com/forum/#!forum/kubernetes-sig-network) <br> [GitHub issues](https://github.com/kubernetes/kubernetes/labels/area%2Fipv6) |
| Cloud Native Governance and Security |  |  |  |  |
|  | [AAD Pod Identity](https://github.com/Azure/aad-pod-identity) | Enables K8s applications to access cloud resources securely with Azure Active Directory | Azure: incubation | [GitHub issues](https://github.com/Azure/aad-pod-identity/issues) |
|  | [OPA Gatekeeper](https://github.com/open-policy-agent/gatekeeper) | K8s native Open Policy Agent policy enforcement | CNCF: incubating <br> API: alpha | [#kubernetes-policy](https://openpolicyagent.slack.com/archives/CDTN970AX) <br> [GitHub issues](https://github.com/open-policy-agent/gatekeeper/issues) |
|  | [Keyvault Flexvol](https://github.com/Azure/kubernetes-keyvault-flexvol) | Mount Azure Keyvault secrets into pods | Azure: sandbox | [GitHub issues](https://github.com/Azure/kubernetes-keyvault-flexvol/issues) |
|  | [Secrets Store CSI Driver](http://sigs.k8s.io/secrets-store-csi-driver) | Integrates secrets stores with Kubernetes via a [Container Storage Interface (CSI)](https://kubernetes-csi.github.io/docs/) volume | CNCF: sandbox? | [GitHub issues](https://github.com/kubernetes-sigs/secrets-store-csi-driver/issues) |
|  | [Azure KeyVault Provider for Secrets Store CSI Driver](https://github.com/Azure/secrets-store-csi-driver-provider-azure) | Enables mounting AKV secrets as volumes in K8s pods | Azure: sandbox | [GitHub issues](https://github.com/Azure/secrets-store-csi-driver-provider-azure/issues) |
| Cloud Native Service Mesh |  |  |  |  |
|  | [Service Mesh Interface (SMI)](https://smi-spec.io/) | A standard interface for service meshes on Kubernetes | Azure: sandbox? | [#general](https://smi-spec.slack.com/archives/CJJF5M5NK) |
|  |  |  |  |  |

To make a correction to this list, please create and issue or a pull request.
