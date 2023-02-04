## Continuous deployment to Kubernetes cluster using ArgoCD and Kustomize 

## Best practice for Git Repository 
1. Application source code in different repository - https://github.com/lanru2001/nodejs-react-user-mgt-app
2. Application configuration ( k8s manifest file) in another repository.

# Install argocd on EKS Cluster

```bash
kubectl create namespace argocd
kubectl apply -n argocd -f https://raw.githubusercontent.com/argoproj/argo-cd/stable/manifests/install.yaml
```
