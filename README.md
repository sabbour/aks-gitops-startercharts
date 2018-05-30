# aks-gitops-startercharts
Repository containing Helm starter charts to create a Git driven Kubernetes workflow

## Installation

```sh
git clone https://github.com/sabbour/aks-gitops-startercharts ${HOME}/.helm/starters/gitops-startercharts
```

## Updates

```sh
cd ${HOME}/.helm/starters/gitops-startercharts
git pull
```

## Usage

```sh
helm create chart --starter=gitops-startercharts/public-ingress-app your-chart-name
```
