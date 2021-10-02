1) Instalar terraform - https://www.terraform.io/downloads.html
https://www.terraform.io/docs/cli/install/apt.html
2) Aprendendo usando o provider registry da digital ocean
https://registry.terraform.io/providers/digitalocean/digitalocean/latest
3) Como usar em https://registry.terraform.io/providers/digitalocean/digitalocean/latest/docs
4) Monto arquivo main.tf
que define provider( aws, azure, digital ocean, google, etc)
faz a conexao com o provider e define o recurso
5) terraform init
no diretorio do arquivo main.tf
iniciar o "projeto" terraform
6) terraform plan
mostra o que será feito na minha nuvem definida como provider
também valida se tem algum código errado no main.tf
7) terraform apply
aplica minhas configurações do main.tf
mostra o plan e pede confirmação - digitar yes
8) terraform destroy
apaga tuuuudo