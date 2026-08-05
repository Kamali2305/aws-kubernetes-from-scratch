# aws-kubernetes-from-scratch
# Building a Kubernetes Cluster from Scratch on AWS

Building a Kubernetes cluster from scratch on AWS using Amazon EC2, `containerd`, `kubeadm`, `kubelet`, and `kubectl`.

## Project Objective

This project demonstrates the process of building a Kubernetes cluster from scratch on AWS using Amazon EC2.

The objective is to gain a practical understanding of Kubernetes architecture, including the control plane, worker nodes, networking, container runtime, and cluster management before deploying production workloads on Amazon EKS.

## Architecture Overview

The Kubernetes cluster is deployed on Amazon EC2 instances.

- One EC2 instance acts as the **Kubernetes Control Plane**.
- One EC2 instance acts as the **Worker Node**.
- `containerd` is used as the container runtime.
- `kubeadm` is used to initialize and manage the cluster.
- `kubectl` is used to interact with the Kubernetes API.
- Calico provides networking between cluster components.

## What I Completed

- Connected to AWS using AWS CLI
- Connected to Ubuntu EC2 instances using SSH
- Installed `containerd` as the container runtime
- Installed `kubeadm`, `kubelet`, and `kubectl`
- Enabled IP forwarding
- Initialized the Kubernetes control plane
- Configured `kubectl`
- Installed Calico networking
- Verified the Kubernetes control-plane node was in the Ready state

## Technologies Used

- AWS EC2
- Ubuntu Linux
- AWS CLI
- Kubernetes
- `kubeadm`
- `kubelet`
- `kubectl`
- `containerd`
- Calico Networking

## Next Steps

- Join the worker node to the cluster
- Deploy an application
- Create a Kubernetes Service
- Learn ConfigMaps and Secrets
- Configure Ingress
- Deploy the cluster on Amazon EKS
- Automate the infrastructure using Terraform

## Project Status

### In Progress

This repository will be updated as additional Kubernetes components and Amazon EKS deployments are completed.
