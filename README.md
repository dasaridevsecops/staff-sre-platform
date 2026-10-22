### Staff SRE Platform

1. Install k3d
   winget install --id k3d-io.k3d --exact
2. Cluster Config
```
apiVersion: k3d.io/v1alpha5
kind: Simple
metadata:
  name: staff-sre
servers: 1
agents: 2
options:
  k3s:
    extraArgs:
      - arg: --disable=traefik
        nodeFilters:
          - server:*
```
k3d cluster create --config k3d-cluster.yaml
k3d version
3. 