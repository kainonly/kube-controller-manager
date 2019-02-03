# kube-controller-manager

拉取 k8s.gcr.io 镜像

```shell
docker push kainonly/kube-controller-manager:v1.13.3
// or
docker pull ccr.ccs.tencentyun.com/kainonly/kube-controller-manager:v1.13.3
```

重命名镜像

```shell
docker tag kainonly/kube-controller-manager:v1.13.3 k8s.gcr.io/kube-controller-manager:v1.13.3
// or
docker tag ccr.ccs.tencentyun.com/kainonly/kube-controller-manager:v1.13.3 k8s.gcr.io/kube-controller-manager:v1.13.3
```