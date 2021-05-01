## Welcome to Kubectl notes

1. [kind](./kind.md)
2. [kubectl](./kubectl.md)
3. [pyenv](./pyenv.md)
4. [helm](./helm.md)

### Context

Get current context
```markdown
kubectl config current-context
```

List all the Contexts in a kubeconfig file:

```markdown
kubectl config get-contexts
```

Switch Context:
```markdown
kubectl config use-context <context_name>
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

Describe specific pod in current namespace 

```markdown
kubectl describe pods <pod_name>
```

Describe specific pod in specific namespace

```markdown
kubectl describe pods <pod_name> --namespace=<namespace>
```

Get logs from pod
```
kubectl logs $POD_NAME
```

Save the namespace for all subsequent kubectl commands
```
kubectl config set-context --current --namespace=<insert-namespace-name-here>
# Validate it
kubectl config view --minify | grep namespace:
```

Connect to running containner
```
kubectl exec --stdin --tty <pod_name> -- /bin/bash
```

