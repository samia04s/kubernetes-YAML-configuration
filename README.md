# Kubernetes YAML Configuration Project

This is a beginner-level project to understand and practice writing Kubernetes YAML configuration files.

## 🧠 What I Learned

- Basic structure of a Kubernetes YAML file: `metadata`, `spec`, and `status`
- How to define and create Kubernetes resources like **Pods** and **Deployments**
- How to connect **Services** to **Pods** using `labels`, `selectors`, and `ports`


## 🚀 How to Use

1. Make sure you have **kubectl** and **Minikube** or a Kubernetes cluster set up.
2. Apply the YAML files using:
   
    kubectl apply -f pod.yaml
    kubectl apply -f deployment.yaml
    kubectl apply -f service.yaml

4. Use kubectl get all to see your running resources.

💡 Notes
These files are written for learning purposes.

You can edit labels/selectors to see how changes affect connectivity between services and pods.

** Requirements**
Basic knowledge of terminal/CLI

Kubernetes installed (Minikube or other local cluster)




