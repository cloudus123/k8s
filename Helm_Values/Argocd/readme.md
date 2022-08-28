https://github.com/argoproj/argo-helm/tree/main/charts/argo-cd
helm repo add argo https://argoproj.github.io/argo-helm


Nginx Annotations 			       #line no 1102
Server nginx: true
kubernetes.io/ingress.class: nginx
nginx.ingress.kubernetes.io/force-ssl-redirect: "true"
nginx.ingress.kubernetes.io/ssl-passthrough: "true"
Host: NOT SET

Prometheus Config Refernce Used In Yaml
prometheus label name >> release: m001
Prometheus Namespace Set: monitoring

ServiceMonitor
Application controller metrics: Enabled 	#line no 256 	#Rules/Alert: Disabled
dex metrics: Enabled 				#line no 379
Server Metrics: Enabled 			#line no 1057
Redis: Disabled 				#line no 720
Repo Server: Enabled
applicationset controller: Enabled 		#line no 2026

Redis
Enable Redis: True 				#line no 598
External Redis: Disabled 			#line no 850
Redis HA: Disabled 				#line no 792

Proxy
HA Proxy: Enabled 				#line no 816
HA Proxy Metric: Enabled 			#line no 826

Server 						#Line no 865
Autoscaling: Disabled

Known Host: Enable				#line no 1829
SSh Cred: Disabled 				#line no 1901

Slack Bot: Disabled 				#line no 2633
