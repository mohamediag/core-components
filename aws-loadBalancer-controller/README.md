see https://kubernetes-sigs.github.io/aws-load-balancer-controller/latest/deploy/installation/

```
kustomize build --enable-helm > manifest/manifest.yaml
```

```
wget https://raw.githubusercontent.com/aws/eks-charts/master/stable/aws-load-balancer-controller/crds/crds.yaml
```