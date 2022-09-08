# Kubernetes

The Kubernetes rpm repository. Forthcoming Kubernetes releases will be available once the new release reaches release candidate stage or when the release reaches general availability.

Kubernetes releases are tracked at https://kubernetes.io/releases/ and is the canonical source for upstream lifecycle plans and status. Information on this page may be dated.

|Supported Kubernetes Version | Planned End of Life |
| :--- | ---: |
| 1.25 | 2023-10-27 |
| 1.24   | 2023.07.28 |
| 1.23 | 2023.02.28 |
| 1.22 | 2022.10.28 |

As of August 2022, there is a project to redesign the kubernetes spec file. The repository for this project is at https://github.com/buckaroogeek/copr-k8s-refresh. The corresponding COPR site is https://copr.fedorainfracloud.org/coprs/buckaroogeek/Kubernetes-Refresh/. The existing spec file includes several software components that are now distributed as pods during cluster initiation. The redesign project will refresh the kubernetes rpms and position Fedora as a first class platform for upstream Kubernetes. Enterprise users of Kubernetes clusters may want to explore the capabilities and enhancements in OKD and Openshift. See https://www.okd.io/ for more information.

