## Welcome to Helm


1. [kind](./kind.md)
2. [kubectl](./kubectl.md)
3. [pyenv](./pyenv.md)
4. [helm](./helm.md)


### Repo

List all repo

```markdown
helm repo list
```
We should see somethnig like this :
NAME   	URL                                                 
puppet 	https://puppetlabs.github.io/puppetserver-helm-chart
brigade	https://brigadecore.github.io/charts


list charts in repo

```
helm search repo <repo_name>
```

Output :

NAME                        	CHART VERSION	APP VERSION	DESCRIPTION                                       
brigade/brigade             	1.8.0        	v1.4.0     	Brigade provides event-driven scripting of Kube...
brigade/brigade-github-app  	0.7.1        	v0.4.1     	The Brigade GitHub App, an advanced gateway for...
brigade/brigade-github-oauth	0.3.0        	v0.20.0    	The legacy OAuth GitHub Gateway for Brigade       
brigade/brigade-k8s-gateway 	0.3.0        	           	A Helm chart for Kubernetes                       
brigade/brigade-project     	1.0.0        	v1.0.0     	Create a Brigade project                          
brigade/kashti              	0.6.0        	v0.4.0     	A Helm chart for Kubernetes
