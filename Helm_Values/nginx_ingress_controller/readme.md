helm repo add ingress-nginx https://kubernetes.github.io/ingress-nginx

https://github.com/kubernetes/ingress-nginx/tree/main/charts/ingress-nginx
https://github.com/kubernetes/ingress-nginx/blob/main/docs/user-guide/nginx-configuration/annotations.md
https://neerajswarnkar.medium.com/quick-setup-configuring-wildcard-certificate-issuer-using-letsencrypt-aws-route-53-on-kubernetes-96e78a1e3f39
https://loft.sh/blog/kubernetes-nginx-ingress-10-useful-configuration-options/

watchIngressWithoutClass: false 		#line no 75
name: nginx 					#Name of the ingressClass line no 108
externalTrafficPolicy: Local 			#line no 482
autoscaling: false				#line no 373
internal LoadBalancer: false 			#line no 530
serviceMonitor: Enabled 			#line no 697
prometheusRule: Disabled 			#line no 715
Service LB :Null				#line no 891


