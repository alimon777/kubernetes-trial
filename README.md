# kubernetes-trial
- refer https://kubectlcheatsheet.com/ for kubectl commands
- minikube start --driver=docker    //this is to start minikube(install if not present)
- //create nginx-dep.yaml and nginx-serv.yaml
- kubectl apply -f nginx-dep.yaml
- kubectl get deployments
- kubectl apply -f nginx-serv.yaml
- kubectl get service
- kubectl get pods
- kubectl exec nginxdeploymentpodname -- curl http://localhost
- kubectl get services -o wide
- kubectl port-forward service/nginx-svc 7080:80
