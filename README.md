# FluxCD_With_k8s_kind_cluster
setting up fluxcd on kubernetes Kind cluster locally

## Prerequisites
1. A Kubernetes cluster. We will use Kubernetes kind for trying Flux out in a local development environment.
2. A GitHub personal access token with repo permissions.
3. Docker Daemon... think of docker desktop

## Target
1. Bootstrap Flux on a Kubernetes Cluster
2. Deploy a sample application using Flux
3. Customize application configuration through Kustomize patches

## Get Started with Cluster:
 Use the documentation here to setup and create your local cluster: https://kind.sigs.k8s.io/docs/user/quick-start/#installing-from-source
 
#### For my windows distribution,
 <p> ```go install sigs.k8s.io/kind@v0.11.1 ``` command worked for me!!!
 
 ![image](https://user-images.githubusercontent.com/17796294/146667928-85b705b0-25b4-47d0-b1cf-1b3f2e9a8a97.png)

 
 ![image](https://user-images.githubusercontent.com/17796294/146666565-9b9f87c7-61a3-4dbc-80e1-c2605444245d.png)

### After successful installation
![image](https://user-images.githubusercontent.com/17796294/146666781-4fc4f72e-9a07-43e5-b17f-9a72703136b0.png)


## Install Fluxcd CLI:
Follow the guide below. Depending on your OS distribution.
https://fluxcd.io/docs/installation/#install-the-flux-cli

 ![image](https://user-images.githubusercontent.com/17796294/146667960-632200fe-9308-47c6-a0da-84c5fc50b901.png)

 ```Choco install flux```
 
 ### Install Flux on your Cluster ( In this case it is running locally using Kind)
 * We will github repo. See official documentation when using other Git repos: https://fluxcd.io/docs/installation/
 
