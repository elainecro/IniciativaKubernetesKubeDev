1) Criar cluster kubernetes (digital ocean)
2) Baixar arquivo de configuração
3) Mover para ~/.kube/config
cp diretorio/arquivo.yaml ~/.kube/config
4) kubectl get nodes
para ver os nós da digital ocean
5) aplico o deployment do projeto da aula02
navega até a pasta
kubectl apply -f deployment.digitalocean.yaml
6) kubectl get all
com a opção do type: LoadBalancer no service web, a digital ocean vai me fornecer um ip externo para acessar
7) pega o ip externo gerado e acessa :)
8) era só pra testar, bora apagar
kubectl delete -f deployment.digitalocean.yaml
9) preparar action no github para fazer o deploy na digital ocean