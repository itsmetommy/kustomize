# kustomize

## dev
```
kubectl kustomize overlays/dev
kubectl kustomize overlays/dev | kubectl apply -f -
```

## prod
```
kubectl kustomize overlays/prod
kubectl kustomize overlays/prod | kubectl apply -f -
```

## staging
```
kubectl kustomize overlays/staging
kubectl kustomize overlays/staging | kubectl apply -f -
```