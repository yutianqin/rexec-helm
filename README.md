

```
helm repo add rexec-stack https://yutianqin.github.io/rexec-helm

helm repo update

helm install rexec rexec-stack/rexec-stack -n rexec --create-namespace -f values.yaml


helm install rexec rexec-stack/rexec-stack --version 0.1.0   # gets the old one
helm install rexec rexec-stack/rexec-stack --version 0.1.1   # gets the new one
helm install rexec rexec-stack/rexec-stack                    # gets latest (0.1.1)
```