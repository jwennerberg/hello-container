## hello container

### Deploy with Kustomize

Default deployment:

```sh
kubectl apply --kustomize deploy/
```

Include `hello` namespace:

```sh
kubectl apply --kustomize deploy/overlays/namespace
```
