# k8s-lab

A personal lab for learning and experimenting with Kubernetes (k8s).  
This repo contains manifests, Helm charts, and notes as part of my DevSecOps and cloud-native learning journey.

---

## 📁 Repository Layout
- **manifests/** – YAML files for pods, deployments, services, and ingress  
- **helm-charts/** – Custom or modified Helm charts  
- **labs/** – Hands-on exercises and test projects  
- **notes/** – Study notes, tips, and references  

---

## 🚀 Quick Start

### Prerequisites
- Docker or another container runtime
- [kubectl](https://kubernetes.io/docs/tasks/tools/)
- (Optional) [kind](https://kind.sigs.k8s.io/) or [minikube](https://minikube.sigs.k8s.io/)

### Create a Local Cluster (example with kind)
```bash
kind create cluster --name k8s-lab
kubectl cluster-info --context kind-k8s-lab
