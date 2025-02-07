# 🚀 Setting Up Your Local Kubernetes Environment with Minikube

Welcome to the ultimate guide for setting up your Kubernetes environment with Minikube! 
Follow these simple steps to get everything up and running smoothly. Let's dive in! 🌊🐳

### 1️⃣ Ensure Homebrew is Installed
First, make sure you have Homebrew, the package manager for macOS, installed. If not, you can find it [here](https://brew.sh/).

Install Homebrew with the following command:
```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

### 2️⃣ Verify Homebrew Installation

Check your Homebrew version to ensure it's installed correctly:
```
brew --version
```

### 3️⃣ Ensure Docker is Installed

Docker is our container runtime. Verify its installation with:
```
docker info
```

If Docker isn't installed, no worries! Install it with:
```
brew install --cask docker
```

### 4️⃣ Install Kubectl

Get the command-line tool for Kubernetes:
```
brew install kubectl
```

### 5️⃣ Install Cilium CLI

For network security and observability, install the Cilium CLI:
```
brew install cilium-cli
```

### 6️⃣ Install Tetragon CLI

For runtime security, install the Tetragon CLI:
```
brew install tetra
```
### 7️⃣ Ensure Docker is Running

Make sure Docker is up and running before proceeding! 🏃‍♂️

### 8️⃣ Install Minikube

Get Minikube to run Kubernetes locally:
```
brew install minikube
```
### 9️⃣ Deploy Helm

Helm is the package manager for Kubernetes. Install it with:
```
brew install helm
```

### 🔟 Start Minikube

Time to kickstart your Minikube cluster:

```
minikube start
```

#### NOTE - This will start a minikube control plane with defaults, such a CNI etc. There may be a desire to run without such.

For additional detail see [here](https://minikube.sigs.k8s.io/docs/handbook/)
