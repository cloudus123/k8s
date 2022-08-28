helm repo add ingress-nginx https://kubernetes.github.io/ingress-nginx

https://github.com/kubernetes/ingress-nginx/tree/main/charts/ingress-nginx \
https://github.com/kubernetes/ingress-nginx/blob/main/docs/user-guide/nginx-configuration/annotations.md \
https://neerajswarnkar.medium.com/quick-setup-configuring-wildcard-certificate-issuer-using-letsencrypt-aws-route-53-on-kubernetes-96e78a1e3f39 \
https://loft.sh/blog/kubernetes-nginx-ingress-10-useful-configuration-options/

**Values.yaml Changes** \
watchIngressWithoutClass: false *Tabspace* #line no 75 \
name: nginx *Tabspace* #Name of the ingressClass line no 108 \
externalTrafficPolicy: Local *Tabspace* #line no 482 \
autoscaling: false	*Tabspace* #line no 373 \
internal LoadBalancer: false *Tabspace* #line no 530 \
serviceMonitor: Enabled *Tabspace* #line no 697 \
prometheusRule: Disabled *Tabspace* #line no 715 \
Service LB :Null	*Tabspace* #line no 891
