# kubernetes-trial
- kubectl apply -f nginx-dep.yaml
- kubectl get deployments
- kubectl apply -f nginx-serv.yaml
- kubectl get service
- kubectl get pods
- kubectl exec <nginxdeploymentpodname> -- curl http://localhost
- kubectl get services -o wide
- kubectl port-forward service/nginx-svc 7080:80
