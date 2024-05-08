# kubernetesの練習
テストです

### chapter 4.2.2
```
PS C:\Develop\study\kubernetes-study\chapter04> kubectl get pod --namespace default
E0430 01:18:42.805202   20416 memcache.go:265] couldn't get current server API group list: Get "http://localhost:8080/api?timeout=32s": dial tcp [::1]:8080: connectex: No connection could be made because the target machine actively refused it.
```

クラスタを起動しておく必要がある
> minikube start