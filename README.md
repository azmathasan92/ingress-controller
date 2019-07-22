# ingress-controller

Simple Example:

Clone this repo and then :

step-1: kubectl create -f namespace.yaml

step-2: kubectl create -f default-backend.yaml

step-3: kubectl create -f config-maps.yaml

step-4: kubectl create -f rbac.yaml

step-5: kubectl create -f nginx-ingress-controller.yaml

step-6: kubectl create -f ingress-service.yaml

Ingress-controller has been ready:

now you can create an ingress resource for your services:

kubectl create -f ingress-resource.yaml
