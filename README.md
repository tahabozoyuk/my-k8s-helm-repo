```bash
# my-k8s-helm-github-repo

helm repo add phonebook-repo https://raw.githubusercontent.com/tahabozoyuk/my-k8s-helm-repo/main

helm install phonebook-app my-k8s-helm-repo/phonebook-chart  

- To use own images execute as below

helm install phonebook-app my-k8s-helm-repo/phonebook-chart --set webserver_image=<image-name> --set resultserver_image=<image-name>

```
