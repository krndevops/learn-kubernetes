Learn Kubernetes


Kubernetes Manifest
==========================
APIVERSION(apiVersion)
KIND(kind)
METADATA(metadata)
SPEC(spec)


Install nginx ingress
=============================
helm repo add ingress-nginx https://kubernetes.github.io/ingress-nginx
helm install ngx-ingres ingress-nginx/ingress-nginx