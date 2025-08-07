# Simple Notes App
This is a simple notes app built with React and Django.

## Requirements
1. Python 3.9
2. Node.js
3. React

## Installation
1. Clone the repository
```
git clone <https://>
```

2. Build the app
```
docker build -t notes-app .
```

3. Run the app
```
docker run -d -p 8000:8000 notes-app:latest
```
or 
4. Using K8s
``` 
kubeclt apply -f namespace.yml
kubectl apply -f deployment.yml
kubeclt apply -f service.yml
```
deleting the containers and services
```
kubectl delete -f <fileName.yml>
```

## Nginx

Install Nginx reverse proxy to make this application available

`sudo apt-get update`
`sudo apt install nginx`
