# Para criar o cluster com o arquivo yaml
kind create cluster --name meucluster --config cluster.yaml

# Executar pod
kubectl create -f meupod.yaml

# Apontar porta para o pod
kubectl port-forward pod/meupod 8080:80

# Para criar o replicaset
kubectl apply -f meureplicaset.yaml

# Para criar o deployment
kubectl apply -f meudeployment.yaml