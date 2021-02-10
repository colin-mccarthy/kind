# kind

https://kind.sigs.k8s.io/docs/user/quick-start/#installation

```
brew install golang
```

```
export PATH=$PATH:/Users/colinmccarthy/go/bin
```

```
colinmccarthy@Colins-MacBook-Pro work % kind version
kind v0.10.0 go1.15.7 darwin/amd64
```

## M1 Mac Support

https://hub.docker.com/r/rossgeorgiev/kind-node-arm64

```
kind create cluster --image rossgeorgiev/kind-node-arm64:v1.20.0
```

## context command

```
kubectl cluster-info --context kind-kind
```


## delete cluster

```
kind get clusters

kind delete cluster
```

