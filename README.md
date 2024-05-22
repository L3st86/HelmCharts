# HelmCharts
Helm Charts for HomeLab

Commands for building:
helm lint <chartname>
helm package <chartname>
helm repo index .


Charts and versions:

UptimeKuma - v.0.1.0
Install:
    -helm repo add l3st86 https://l3st86.github.io/HelmCharts/
    -helm install helm l3st86/UptimeKuma 
      with namespace (helm install helm l3st86/UptimeKuma --namespace mi-namespace --set namespace=mi-namespace)
