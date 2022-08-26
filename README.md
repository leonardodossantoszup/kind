# kind

## specify kubernetes version
```bash
kind create cluster --image "kindest/node:v1.18.4" --name kind-cluster --config kind-config.yaml
```

## use default kubernetes version from kind
```bash
kind create cluster --image "kindest/node:v1.17.5" --name kind-cluster --config kind-config.yaml
```

# ingress traefik 1.7

1. rbac

kubectl apply -f https://raw.githubusercontent.com/traefik/traefik/v1.7/examples/k8s/traefik-rbac.yaml

2. daemonset

kubectl apply -f https://raw.githubusercontent.com/traefik/traefik/v1.7/examples/k8s/traefik-ds.yaml
