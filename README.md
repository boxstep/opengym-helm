# OpenGym Helm Chart

[![Helm](https://img.shields.io/badge/Helm-v3-blue.svg)](https://helm.sh/)

Official Helm chart for deploying OpenGym on Kubernetes.

---

## Installation

### 1. Add the Helm Repository

```bash
helm repo add boxstep [https://boxstep.github.io/opengym-helm/](https://boxstep.github.io/opengym-helm/)
helm repo update
helm install opengym boxstep/opengym-helm -f values.yaml 
```