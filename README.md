# minikube

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