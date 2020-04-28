#URLS

- Kubectl Overview: [link](https://kubernetes.io/docs/reference/kubectl/overview/)
- Kubectl cheatsheet: [link](https://kubernetes.io/docs/reference/kubectl/cheatsheet/)

- 

Generate a Deployment YAML but don't create it

`kubectl create deployment --image=nginx nginx --dry-run -o yaml > nginx-deployment.yaml`

You can generate [all these resources](https://kubernetes.io/docs/reference/kubectl/conventions/#generators)

