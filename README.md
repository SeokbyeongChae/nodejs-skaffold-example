# nodejs-skaffold-example

### 1. Intall Ingress-nginx
https://kubernetes.github.io/ingress-nginx/deploy/
```
kubectl apply -f https://raw.githubusercontent.com/kubernetes/ingress-nginx/controller-v1.8.2/deploy/static/provider/cloud/deploy.yaml
```

### 2. Install Skaffold
https://skaffold.dev/docs/install/
```
brew install skaffold
or
choco install -y skaffold
```

### 3. Start Skaffold
```
skaffold dev
```
