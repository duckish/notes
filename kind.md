## Welcome to Kind notes

1. [kind](./kind.md)
2. [kubectl](./kubectl.md)
3. [pyenv](./pyenv.md)
4. [helm](./helm.md)

### Cluster

Create cluster

```markdown
kind create cluster
```
Load local image to kind cluster --name is for cluster name if we don't name cluster, it is not need

```
kind load docker-image my-custom-image --name kind-2
```
