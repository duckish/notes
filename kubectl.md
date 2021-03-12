## Welcome to Kubectl notes

1. [kind](./kind.md)
2. [kubectl](./kubectl.md)
3. [pyenv](./pyenv.md)

### Context

Show contexts

```markdown
kubectl config get-contexts
```

List all namespaces

Docs : https://kubernetes.io/docs/concepts/overview/working-with-objects/namespaces/ 

```markdown
kubectl get namespace
```

List all pods in current namespace 

```markdown
kubectl get pods
```

Describe specific pod 

```markdown
kubectl describe pods <pod_name>
```


