# deploy mongoDB and mongo-express
## to run the app
```bash
kubectl create -f mongo_sec.yaml
kubectl create -f mongo-configmap.yaml
kubectl create -f mongodb.yaml
kubectl create -f mongo-express.yaml
```
### then type
```bash
minikune ip
```
#### type in browser   minikune ip:30119

![194866518-1f79a190-f6f3-4a23-bb72-53f314fc29aa](https://user-images.githubusercontent.com/29188579/205309515-1ede547c-515f-4438-b66e-36431d374cd6.png)
