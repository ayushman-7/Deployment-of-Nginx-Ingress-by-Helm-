# ingress-nginx

[ingress-nginx](https://github.com/kubernetes/ingress-nginx) Ingress controller for Kubernetes using NGINX as a reverse proxy and load balancer

![Version: 4.10.1](https://img.shields.io/badge/Version-4.10.1-informational?style=flat-square) ![AppVersion: 1.10.1](https://img.shields.io/badge/AppVersion-1.10.1-informational?style=flat-square)

To use, add `ingressClassName: nginx` spec field or the `kubernetes.io/ingress.class: nginx` annotation to your Ingress resources.

This chart bootstraps an ingress-nginx deployment on a [Kubernetes](http://kubernetes.io) cluster using the [Helm](https://helm.sh) package manager.

