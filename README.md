### Deployments

Deployment configuration files for starting a cluster in Docker Compose and Kubernetes.

- docker-compose/ - a simple local deployment in Docker Compose
- kubernetes/helm/minikube/ - minikube deployment with Nginx Ingress Controller
- kubernetes/helm/k3s/ - k3s deployment with Nginx Ingress Controller
- kubernetes/helm/talos/ - Talos deployment with Traefik Ingress Controller

---

#### Notes

- Resource parameters in _values.yaml_ are for a cohort the size of 1000 Genomes Project Dataset (3202 WGS).
- Cluster in _k3s_ is configured with _Aeron UDP_. In Talos it is configured with _Artery TCP_.