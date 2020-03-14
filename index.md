# Container
## Docker
## Create a docker image

## Tag an image

## Push an image to a registry

# Getting a k8s cluster
## Local machine

## Azure AKS
### Using ARM templates
1. Generate ssh key

`ssh-keygen -t rsa -b 2048`

2. Create a service principle

`az ad sp create-for-rbac --skip-assignment`

## google Cloud

# Pod

# Installing kubectl

## Mac

## Linux

## Setting autocomplete and alias

# Pod
## Pod lifecycle management
## Create a pod

## Delete a pod

## Label a pod

## Describe a pod

# ReplicaSet

# Service
## Expose a service quickly
`kubectl expose rc kubia --type=LoadBalancer --name kubia-http`
# Inside the container
## Execute a command 
`kubectl exec kubia-7nog1 -- curl -s http://10.111.249.153`

# Deployment
