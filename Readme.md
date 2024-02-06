KIND 

https://kind.sigs.k8s.io/docs/user/configuration/

curl -LO https://dl.k8s.io/release/$(curl -L -s https://dl.k8s.io/release/stable.txt)/bin/darwin/arm64/kubectl

chmod +x kubectl 

sudo mv ./kubectl /usr/local/bin/kubectl
