## Kubernetes Desired Manifest vs Live Manifest

| Feature | Desired Manifest | Live Manifest |
|---|---|---|
| **Definition** | The intended state of your application. | The actual state of your resources in the cluster. |
| **Location** | Stored in Git, Helm charts, or Kustomize templates. | Stored directly in the Kubernetes API and etcd. |
| **Purpose** | To define configuration rules for deployments, pods, and services. | To reflect the current runtime environment, including assigned IPs, node scheduling, and resource status. |
| **Changes** | Updated by developers pushing code or configuration updates. | Updated automatically by Kubernetes controllers over time. |
