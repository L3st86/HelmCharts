# duplicati

![Version: 0.1.0-beta.2](https://img.shields.io/badge/Version-0.1.0-beta.2-informational?style=flat-square) ![AppVersion: 1.16.1](https://img.shields.io/badge/AppVersion-1.16.1-informational?style=flat-square)
[![Artifact Hub](https://img.shields.io/endpoint?url=https://artifacthub.io/badge/repository/helm-l3st86)](https://artifacthub.io/packages/search?repo=helm-l3st86)
duplicati Helm Chart (Backups)

## Source Code

* <https://github.com/linuxserver/docker-duplicati>

## Requirements

Kubernetes: `>=1.16.0-0`

## TL;DR

```console
helm repo add l3st86 https://l3st86.github.io/HelmCharts/
helm repo update
helm install duplicati l3st86/duplicati
```

## Installing the Chart

To install the chart in namespace 'backups'
```console
helm install duplicati l3st86/duplicati --namespace backups --set namespace=backups
```

## Uninstalling the Chart

To uninstall the `duplicati` deployment

```console
helm uninstall duplicati
```

The command removes all the Kubernetes components associated with the chart **including persistent volumes** and deletes the release.

## Configuration

Read through the [values.yaml](./values.yaml) file. It has several commented out suggested values.
Alternatively, a YAML file that specifies the values for the above parameters can be provided while installing the chart.

```console
helm install duplicati l3st86/duplicati -f values.yaml
```

## Changelog

### Version 0.1.0-beta.2

#### Added

First Version Beta in progress

#### Changed

* Upgraded Release Notes