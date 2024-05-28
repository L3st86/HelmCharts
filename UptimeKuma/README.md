# uptime-kuma

![Version: 0.1.9](https://img.shields.io/badge/Version-0.1.9-informational?style=flat-square) ![AppVersion: 0.1.9](https://img.shields.io/badge/AppVersion-0.1.9-informational?style=flat-square)
[![Artifact Hub](https://img.shields.io/endpoint?url=https://artifacthub.io/badge/repository/helm-l3st86)](https://artifacthub.io/packages/search?repo=helm-l3st86)
Monitoring Tool Uptime Kuma Chart

## Source Code

* <https://github.com/louislam/uptime-kuma>

## Requirements

Kubernetes: `>=1.16.0-0`

## TL;DR

```console
helm repo add l3st86 https://l3st86.github.io/HelmCharts/
helm repo update
helm install kuma l3st86/UptimeKuma
```

## Installing the Chart

To install the chart in namespace 'monitoring'
```console
helm install kuma l3st86/UptimeKuma --namespace monitoring --set namespace=monitoring
```

## Uninstalling the Chart

To uninstall the `kuma` deployment

```console
helm uninstall kuma
```

The command removes all the Kubernetes components associated with the chart **including persistent volumes** and deletes the release.

## Configuration

Read through the [values.yaml](./values.yaml) file. It has several commented out suggested values.
Alternatively, a YAML file that specifies the values for the above parameters can be provided while installing the chart.

```console
helm install kuma l3st86/UptimeKuma -f values.yaml
```

## Changelog

### Version 0.1.9

#### Added

N/A

#### Changed

* Upgraded Release Notes