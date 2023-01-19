# Kubernetes

The Kubernetes rpm repository. Forthcoming Kubernetes releases will be available once the new release reaches release candidate stage or when the release reaches general availability.

Kubernetes releases are tracked at https://kubernetes.io/releases/ and is the canonical source for upstream lifecycle plans and status. Information on this page may be dated. The golang version in the table below is the major:minor version used by upstream to build and test the release. The specific patch release can change.

|Supported Kubernetes Version | Planned End of Life | Golang Built With |
| :--- | --- | ---: |
| 1.26 | 2024.02.24 | 1.19* |
| 1.25 | 2023.10.27 | 1.19 |
| 1.24   | 2023.07.28 | 1.18 |
| 1.23 | 2023.02.28 | 1.17, 1.19** |
| 1.22 | 2022.10.28 | 1.16 |

*Expect the version of go used for 1.26 to change.
**As of version 1.23.15, now built with go 1.19.4.

Kubernetes 1.23 did not make it into an official Fedora package. Unofficial packages for Fedora 36 and Fedora 37 can be found in COPR at https://copr.fedorainfracloud.org/coprs/buckaroogeek/copr-k8s-1.23/.

As of August 2022, there is a project to redesign the kubernetes spec file. The repository for this project is at https://github.com/buckaroogeek/copr-k8s-refresh. The corresponding COPR site is https://copr.fedorainfracloud.org/coprs/buckaroogeek/Kubernetes-Refresh/. The existing spec file includes several software components that are now distributed as pods during cluster initiation. The redesign project will refresh the kubernetes rpms and position Fedora as a first class platform for upstream Kubernetes. Enterprise users of Kubernetes clusters may want to explore the capabilities and enhancements in OKD and Openshift. See https://www.okd.io/ for more information.

