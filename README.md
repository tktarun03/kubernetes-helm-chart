# kubernetes-helm-chart

A basic Helm chart to deploy a simple web application on Kubernetes.

## 🚀 Features
- Uses **Helm** to deploy a sample web application on **Kubernetes**.
- Configurable **replicas, image, service, and ingress**.
- Simplifies Kubernetes deployments.

## 📂 Project Structure
```
kubernetes-helm-chart/
│── helm-chart/
│   ├── Chart.yaml  # Helm chart metadata
│   ├── values.yaml  # Default configuration
│   ├── templates/  # Kubernetes YAML templates
│── README.md
```

## 🛠 Installation & Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/tktarun03/kubernetes-helm-chart.git
   cd kubernetes-helm-chart/helm-chart
   ```

2. Install the Helm chart on a Kubernetes cluster:
   ```bash
   helm install my-web-app .
   ```

3. Verify deployment:
   ```bash
   kubectl get pods
   kubectl get services
   ```

## 👨‍💻 About the Author

🚀 Created by [Arunkumar Thamilarasu](https://github.com/tktarun03) | UI Technical Architect | Kubernetes & DevOps Expert

## ⭐ Contribute & Support
- Fork & Star this repository! ⭐
- Submit Issues and PRs to improve the Helm chart.

---
🎯 **Follow me on GitHub**: [@tktarun03](https://github.com/tktarun03)
