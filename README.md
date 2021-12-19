# FluxCD_With_k8s_kind_cluster
setting up fluxcd on kubernetes Kind cluster locally

## Prerequisites
1. A Kubernetes cluster. We will use Kubernetes kind for trying Flux out in a local development environment.
2. A GitHub personal access token with repo permissions.

## Target
1. Bootstrap Flux on a Kubernetes Cluster
2. Deploy a sample application using Flux
3. Customize application configuration through Kustomize patches

## Get Started with Cluster:
 Use the documentation here to setup and create your local cluster: https://kind.sigs.k8s.io/docs/user/quick-start/#installing-from-source
 ![image](https://user-images.githubusercontent.com/17796294/146666565-9b9f87c7-61a3-4dbc-80e1-c2605444245d.png)

### After successful installation
![image](https://user-images.githubusercontent.com/17796294/146666781-4fc4f72e-9a07-43e5-b17f-9a72703136b0.png)


## Install Fluxcd CLI:
Follow the guide below. Depending on your OS distribution.
https://fluxcd.io/docs/installation/#install-the-flux-cli
