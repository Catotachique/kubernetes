# kubernetes
Project about Kubernetes

# Kubernetes with Go: Feature & Tooling Guide
## Overview

This guide provides a quick reference to different Kubernetes features you can implement using Go and the associated tools/libraries.

| **Feature**               | **Use Go to...**                    | **Tooling**                    |
|---------------------------|-------------------------------------|--------------------------------|
| **CRDs**                  | Define new resource types           | Kubebuilder                    |
| **Controllers/Operators** | Implement logic to reconcile state  | controller-runtime             |
| **Admission Controllers** | Validate/mutate API objects         | Webhooks                       |
| **CLI Tools**             | Build custom kubectl-style tools    | Cobra, client-go               |
| **Scheduler**             | Customize pod scheduling            | Scheduler Plugins              |
| **API Server**            | Add new API endpoints               | Aggregated APIs                |
| **Cloud Integration**     | Hook into cloud APIs                | Cloud Controller Manager (CCM) |
| **Storage/Devices**       | Support custom hardware             | CSI/Device Plugins             |
|---------------------------|-------------------------------------|--------------------------------|