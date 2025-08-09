# mosquito-mqtt

![Version: 0.1.2](https://img.shields.io/badge/Version-0.1.2-informational?style=flat-square) ![AppVersion: 1.16.0](https://img.shields.io/badge/AppVersion-1.16.0-informational?style=flat-square)
[![Artifact Hub](https://img.shields.io/endpoint?url=https://artifacthub.io/badge/repository/helm-l3st86)](https://artifacthub.io/packages/search?repo=helm-l3st86)
mosquito-mqtt Helm Chart (Backups)

## Source Code

* <https://github.com/linuxserver/docker-mosquito-mqtt>

## Requirements

Kubernetes: `>=1.16.0-0`

## TL;DR

```console
helm repo add l3st86 https://l3st86.github.io/HelmCharts/
helm repo update
helm install mosquito-mqtt l3st86/mosquito-mqtt
```

## Installing the Chart

To install the chart in namespace 'home-assistant'
```console
helm install mosquito-mqtt l3st86/mosquito-mqtt --namespace home-assistant --set namespace=home-assistant
```

## Uninstalling the Chart

To uninstall the `mosquito-mqtt` deployment

```console
helm uninstall mosquito-mqtt
```

The command removes all the Kubernetes components associated with the chart **including persistent volumes** and deletes the release.

## Configuration

Read through the [values.yaml](./values.yaml) file. It has several commented out suggested values.
Alternatively, a YAML file that specifies the values for the above parameters can be provided while installing the chart.

```console
helm install mosquito-mqtt l3st86/mosquito-mqtt -f values.yaml
```

## Changelog

#### Changed

* First Version Working

### Version 0.1.2

