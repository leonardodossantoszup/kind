# kind

## specify kubernetes version
```bash
kind create cluster --image "kindest/node:v1.18.4" --name kind-cluster --config kind-config.yaml
```

## use default kubernetes version from kind
```bash
kind create cluster --image "kindest/node:v1.17.5" --name kind-cluster --config kind-config.yaml
```