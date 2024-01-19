## Apply kubect config

at kubectl config dir

```bash
kubectl apply -f [configfile_name]
```

## Restart deployment

```bash
kubectl rollout restart deployment [depl_name]
```

## Start skaffold

```bash
# on root dir
skaffold dev
```
