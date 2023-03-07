# Backstage template EKS Kubernetes cluster

Template for an EKS cluster

## Add to your own Backstage catalog

To add this to your own `/app-config.yaml: catalog.locations` array

```yaml
# add under /app-config.yaml catalog.locations
- type: url
  target: https://github.com/jujhar-teaching-org/backstage-template-infra-k8s-cluster/blob/main/backstage-catalog-template.yaml
  rules:
    - allow: [Template]
```
