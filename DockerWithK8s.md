# Using Docker with k8s

This manual is target Mac user with Homebrew.

## Docker 

### What is Docker

### Install Docker
```
brew cask install docker
```
Start docker and login with your account and password

## Install Kubernetes and minikube

### What is Kubernetes

### What is minikube

### Install Kubernetes and minikube
```
brew install kubernetes-cli
brew cask install minikube
```

# install and setup VM for minikube
```
brew install docker-machine-driver-hyperkit
sudo chown root:wheel /usr/local/opt/docker-machine-driver-hyperkit/bin/docker-machine-driver-hyperkit
sudo chmod u+s /usr/local/opt/docker-machine-driver-hyperkit/bin/docker-machine-driver-hyperkit
```

### Run minikube 

```
sudo minikube start --vm-driver hyperkit
sudo minikube dashboard
```