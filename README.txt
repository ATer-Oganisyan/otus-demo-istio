Installation manual

Run:

alias k=kubectl
helm repo add myZql https://charts.bitnami.com/bitnami		
helm install myzql-release myZql/mysql -f ./mysql/values.yml
k apply -f ./mysql/migrations/  
k apply -f ./

Import Simple_CRUD.postman_collection.json into Postman.

Enjoy :)


minikube start --cpus=4 --memory=8g --cni=flannel --kubernetes-version="v1.19.0"

## docker build -t arsenteroganisyan/otus-http-server /Users/arsen/otus-istio/otus-demo-istio/v3.1 --no-cache --platform linux/amd64