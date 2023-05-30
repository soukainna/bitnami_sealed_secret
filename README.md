# bitnami_sealed_secret

## Pré-requis

#### kubernetese, Argo CD

## Instalation

### kubeseal

wget https://github.com/bitnami-labs/sealed-secrets/releases/download/v0.21.0/kubeseal-0.21.0-linux-amd64.tar.gz 

tar -xvf kubeseal-0.21.0-linux-amd64.tar.gz 

chmod +x kubeseal

mv kubeseal /user/local/bin

### Installing Controller via Kubectl

wget https://github.com/bitnami-labs/sealed-secrets/releases/download/v0.21.0/controller.yaml

kubectl apply -f controller.yaml





