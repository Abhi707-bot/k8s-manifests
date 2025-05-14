# k8s-manifests

# Kubernetes Ingress Controller Example (Minikube + NGINX)

This project demonstrates how to set up an **NGINX Ingress Controller** in a cloud-native Kubernetes cluster and expose multiple services (backend and frontend) using clean URLs.

---

## 📦 Project Structure

```bash
.
├── backend.yml          # NGINX backend deployment + service
├── frontend.yml         # Apache frontend deployment + service
├── ingress.yml          # Ingress resource to route traffic
└── README.md
