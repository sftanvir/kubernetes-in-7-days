### Kubectl
https://kubernetes.io/docs/tasks/tools/install-kubectl/
### Install kubectl on Linux
```
curl -LO https://storage.googleapis.com/kubernetes-release/release/`curl -s https://storage.googleapis.com/kubernetes-release/release/stable.txt`/bin/linux/amd64/kubectl
chmod +x ./kubectl
sudo mv ./kubectl /usr/local/bin/kubectl
kubectl version
```
```
sudo snap install kubectl --classic
brew install kubernetes-cli
```
### Virtual Box
https://www.oracle.com/virtualization/technologies/vm/downloads/virtualbox-downloads.html
### Minikube
https://github.com/kubernetes/minikube/releases
```
curl -LO https://storage.googleapis.com/minikube/releases/latest/minikube_1.3.1.deb
sudo dpkg -i minikube_1.3.1.deb
```
### Helm
https://github.com/helm/helm/releases
```
curl -L https://storage.googleapis.com/kubernetes-helm/helm-v2.9.1-darwin-amd64.tar.gz | tar xzvf -
sudo mv darwin-amd64/helm /usr/local/bin/
rm -Rf darwin-amd64
```
### Kubectx and Kubens
https://github.com/ahmetb/kubectx
https://brew.sh/
```
brew install kubectx --with-short-names
```
### Kubetail
https://github.com/johanhaleby/kubetail
```
brew tap johanhaleby/kubetail && brew install kubetail
```
