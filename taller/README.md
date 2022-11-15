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
