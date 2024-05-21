# HelmCharts

## Helm Charts for HomeLab
Charts and versions:

UptimeKuma - v.0.1.4

### Commands for building:

```sh
helm lint <chartname>
helm package <chartname>
```
### Commands for building:
```sh
helm repo add l3st86 https://l3st86.github.io/HelmCharts/
helm install helm l3st86/UptimeKuma
helm install helm l3st86/UptimeKuma --namespace mi-namespace --set namespace=mi-namespace
```
