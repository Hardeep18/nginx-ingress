# nginx-ingress
Nginx ingress controller


## Installed nginx ingress deployment 

kubectl -n ingress-nginx apply -f https://raw.githubusercontent.com/kubernetes/ingress-nginx/controller-v0.41.2/deploy/static/provider/cloud/deploy.yaml


## Apply domain routing 

kubectl apply -f app-ui.yml -f app-api.yml
