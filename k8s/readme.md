### Creating an Nginx Pod via Command 
> kubectl run nginx --image=nginx --port=80 --port=443 --dry-run=client -o yaml
>

### Apply changes in yaml file
> kubectl apply -f filename.yaml
>
Example
kubectl apply -f deploy.yaml