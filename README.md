# minikube

## instalación docker,minikube y kubectl

````bash
https://www.linuxtechi.com/install-use-docker-on-ubuntu/
https://www.linuxtechi.com/how-to-install-minikube-on-ubuntu/
sudo usermod -aG docker $USER && newgrp docker
git config --global user.name "andres naranjo"
git config --global user.email afnarqui@hotmail.com
git clone https://github.com/afnarqui/minikube.git
````

## comandos kubectl

````bash
kubectl version --client
kubectl run  podtest2 --image=nginx:alpine
kubectl get pods
kubectl describe pod podtest2
kubectl delete pod podtest2
kubectl api-resources
kubectl run  podtest2 --image=nginx:alpine
kubectl get pod podtest2 -o yaml
docker ps -a
kubectl exec -it podtest2 sh
curl 172.17.0.3
pdw
whoami
cd /usr/share/nginx/html
cat cd /usr/share/nginx/html/index.html
kubectl logs podtest2 -f

kubectl apply -f pod.yml
kubectl get pods
docker run --net host -ti python:3.6-alpine sh
# python -m http.server 8081
````