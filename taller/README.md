# Taller

## Clonar el Repositorio

```
git clone https://github.com/luisvillarreal/itpn-k8s.git
```

## Usando Cloud Shell

### Listar los clusters de K8s
```
gcloud container clusters list
```

### Obtener credenciales del cluster
```
gcloud container clusters get-credentials NOMBRE_DEL_CLUSTER --zone ZONA_DEL_CLUSTER
```

### Listar Nodos del cluster
```
kubectl get nodes
```


### Crear Namespace
```
kubectl create ns w255
```

### Aplicar configuracion de archivo
```
kubectl apply -f NOMBRE_DE_ARCHIVO.yaml
```

### Borrar pod
```
kubectl delete pod -n NAMESPACE NOMBRE_DEL_POD
```

### Escalar Deployment
```
kubectl scale deployment.apps/NOMBRE_DEL_DEPLOYMENT -n NAMESPACE --replicas NUMERO
```

### Obtener direccion IP Externa del Servicio
```
kubectl get svc -n NAMESPACE
```

### Visualizar Pagina Web
En una pestana del navegador de Internet
```
http://DIRECCION_DE_IP_DEL_SERVICIO
```

### Destruir Cluster
```
gcloud container clusters delete NOMBRE_DEL_CLUSTER --zone ZONA_DEL_CLUSTER
```

