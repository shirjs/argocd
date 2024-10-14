creating a service for argocd of type nodeport
optionally put it in namespace: argocd
port exposed within cluster: 443
the port inside the pod: 8080
external port on which this will be avialable on the entire cluster: 30007
selector: which port will be targeted

