# OTA UK V job runner

Create: `helm install ota-uk-v --name=ota-uk-v --namespace=impact-lab`

Update: 
```shell
kubectl -n impact-lab delete jobs ota-uk-v
helm upgrade ota-uk-v ota-uk-v
```