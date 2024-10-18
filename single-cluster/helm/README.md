```
kind: GitRepo
apiVersion: fleet.cattle.io/v1alpha1
metadata:
  name: hello
  namespace: fleet-default
spec:
  repo: https://github.com/mrolmedo/fleet-examples.git
  paths:
  - single-cluster/helm
  targets:
    - clusterName: clustername
```
