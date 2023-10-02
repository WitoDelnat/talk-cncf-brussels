# CNCF Brussels

## Prerequisites

Start a cluster with validation admission controller enabled:

```
kind create cluster \
    --name vap-beta \
    --image kindest/node:v1.28.0 \
    --config cluster.yaml
```
