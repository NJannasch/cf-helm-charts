# Cloudflare Helm Charts

### About
A convenient location to publish Cloudflare helm charts

### Setup
```bash
helm repo add nils-cloudflare https://njannasch.github.io/cf-helm-charts/
helm repo update
```

### Discovery
```bash
helm search nils-cloudflare
```

### Contents
- `charts/argo-tunnel`: (Deprecated) the former ingress based helm chart
- `charts/cloudflare-tunnel`: Helm 3 chart using cloudflared best practices
