# GCP Kubernetes High Availability

* Self-managed Kubernetes High Availability in Google Compute Engine
* This guide is not for people looking for a fully automated command to bring up a Kubernetes cluster
* GCE use because sctp needed for open5gs, GKE nodes do not support sctp, it was failed in GKE, if later GCP support sctp in GKE nodes, probably better to use GKE.
* Calico, Containerd, Kubernetes v1.22.x, ROOK, CEPH, HELM, Istio, Open5Gs, Rancher, nginx
* The results of this tutorial should not be viewed as production ready, and may receive limited support from the community, but don’t let that stop you from learning!

## Topology

![kubernetes.io-screenshot](docs/images/kubernetes_HA.JPG)
source : kubernetes.io

## Topology GCP
![kubernetes.gcp-screenshot](docs/images/gcp_k8s_ha.png)


## Labs

This tutorial assumes you have access to the [Google Cloud Platform](https://cloud.google.com). While GCP is used for basic infrastructure requirements the lessons learned in this tutorial can be applied to other platforms.

* [Prerequisites](docs/01-prerequisites.md)
