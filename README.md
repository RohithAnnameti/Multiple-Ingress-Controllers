# Multiple-Ingress-Controllers

1. Create an first nginx ingress controller using kubectl command
   kubectl apply -f https://raw.githubusercontent.com/kubernetes/ingress-nginx/main/deploy/static/provider/cloud/deploy.yaml

2. create an second nginx ingress controller using the Yaml file which is present in this repository. Make sure to change the Namespace, controllerclass and ingress class.
