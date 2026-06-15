kubectl apply -f secret.yml
kubectl apply -f configmap.yml
kubectl apply -f init-sql-configmap.yml
kubectl apply -f postgres-pvc.yml
kubectl apply -f postgres-deployment.yml
kubectl apply -f postgres-service.yml
kubectl apply -f bookapp-deployment.yml
kubectl apply -f bookapp-service.yml


**Access App on http://<node-ip>:30080**
