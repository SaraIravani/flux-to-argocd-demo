
# 🌟 flux-to-argocd-demo

This demo project demonstrates the **conversion** of an existing **Flux-based Kubernetes deployment** into **ArgoCD YAML configurations**.

## 📂 Project Structure

```bash
flux-to-argocd-demo/
├── flux/
│   ├── gotk-components.yaml  # Flux components installation
│   ├── gotk-sync.yaml       # Flux sync configuration
│   └── kustomization/       # Kustomize-based deployment
│       ├── deployment.yaml  # NGINX Deployment in Flux
│       └── kustomization.yaml
├── argocd/
│   ├── application.yaml     # ArgoCD application configuration
│   └── nginx/
│       ├── deployment.yaml  # NGINX Deployment in ArgoCD
│       └── service.yaml     # NGINX Service in ArgoCD
```

## 🚀 What’s Included

- **Flux Setup**:  
  - Flux components (`gotk-components.yaml`)  
  - Flux sync (`gotk-sync.yaml`)  
  - Kustomize-based deployment (`kustomization/` folder)

- **ArgoCD Setup**:  
  - ArgoCD Application configuration (`application.yaml`)  
  - Equivalent NGINX app deployment (`nginx/` folder)

## 🔧 How to Use

1. **Clone this repository**:
   ```bash
   git clone https://github.com/sarairavani/flux-to-argocd-demo.git
   ```
2. **Deploy Flux**:
   - Apply the Flux components and sync files to your Kubernetes cluster.
3. **Deploy ArgoCD**:
   - Apply the `application.yaml` and corresponding NGINX deployment and service.

## 📈 Why This Matters

- **Flux to ArgoCD Migration**: Perfect for engineers transitioning between GitOps tools.
- **Practical Use Case**: Shows real-world deployment of a Kubernetes app with two major GitOps tools.
- **Organized & Scalable**: Can be expanded with more complex examples or custom applications.

## 📚 Resources

- [Flux Documentation](https://fluxcd.io/docs/)
- [ArgoCD Documentation](https://argo-cd.readthedocs.io/en/stable/)

---

### 💬 About the Author

Made with ❤️ by **Sara**, a DevOps Engineer passionate about Kubernetes, GitOps, and automated infrastructure.
