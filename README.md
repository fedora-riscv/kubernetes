# Kubernetes

The Kubernetes rpm repository. Forthcoming Kubernetes releases will be available once the new release reaches release candidate stage or when the release reaches general availability.

Kubernetes releases are tracked at https://kubernetes.io/releases/ and is the canonical source for upstream lifecycle plans and status. Information on this page may be dated. The golang version in the table below is the major:minor version used by upstream to build and test the release. The specific patch release can change.

| Kubernetes Version | Target Fedora Release | Kubernetes Planned End of Life | Golang Built With |
| :--- | --- | --- | ---: |
| 1.27 | F39 | 2024.06.28 | 1.20 |
| 1.26 | F38 | 2024.02.24 | 1.19*1 |
| 1.25 | F37 | 2023.10.27 | 1.19 |
| 1.24   | F36*2-EOL | 2023.07.28 | 1.18/1.19 |
| 1.23 | COPR-EOL | 2023.02.28 | 1.17, 1.19*3 |
| 1.22 | F35-EOL | 2022.10.28 | 1.16 |

*1 Expect the version of go used for 1.26 to change.

*2 As of v.1.24.10 Kubernetes is built with go 1.19.x. F36 originally provided go 1.18 blocking this and future Kubernetes updates. Go 1.19 was approved for F36 so starting with Kubernetes 1.24.11 (K8S 1.24.10 is available at https://copr.fedorainfracloud.org/coprs/buckaroogeek/copy-k8s-1.24/ if needed).

*3 As of version 1.23.15, now built with go 1.19.4 or newer.

Kubernetes 1.23 did not make it into an official Fedora package. Unofficial packages for Fedora 36 and Fedora 37 can be found in COPR at https://copr.fedorainfracloud.org/coprs/buckaroogeek/copr-k8s-1.23/.

