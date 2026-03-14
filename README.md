

```
helm repo add rexec-stack https://yutianqin.github.io/rexec-helm

helm repo update

helm install rexec rexec-stack/rexec-stack -n rexec --create-namespace -f values.yaml
```