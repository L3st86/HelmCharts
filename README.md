# HelmCharts

## Helm Charts for HomeLab
Charts and versions:

UptimeKuma - v.0.1.4

### Commands for building:

```sh
helm lint <chartname>
helm package <chartname>
```
### Commands for Deploy with helm:
```sh
helm repo add l3st86 https://l3st86.github.io/HelmCharts/
helm install kuma l3st86/UptimeKuma
helm install kuma l3st86/UptimeKuma --namespace my-namespace --set namespace=my-namespace
```
