# HelmCharts

## Helm Charts for HomeLab
Repository: [GitHub Repo](https://github.com/L3st86/HelmCharts)

Charts and versions:

UptimeKuma - v.0.1.9
### Deploy Uptime Kuma with helm:
```sh
helm repo add l3st86 https://l3st86.github.io/HelmCharts/
helm install kuma l3st86/UptimeKuma
helm install kuma l3st86/UptimeKuma --namespace my-namespace --set namespace=my-namespace
```


### Notes - Commands for building Charts:
```sh
helm lint <chartname>
helm package <chartname>
helm repo index .
```