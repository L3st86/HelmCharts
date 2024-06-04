# jellyfin

![Version: 0.1.2](https://img.shields.io/badge/Version-0.1.2-informational?style=flat-square) ![AppVersion: 1.16.0](https://img.shields.io/badge/AppVersion-1.16.0-informational?style=flat-square)
[![Artifact Hub](https://img.shields.io/endpoint?url=https://artifacthub.io/badge/repository/helm-l3st86)](https://artifacthub.io/packages/search?repo=helm-l3st86)
jellyfin Helm Chart (Backups)

## Source Code

* <https://github.com/linuxserver/docker-jellyfin>

## Requirements

Kubernetes: `>=1.16.0-0`

## TL;DR

```console
helm repo add l3st86 https://l3st86.github.io/HelmCharts/
helm repo update
helm install jellyfin l3st86/jellyfin
```

## Installing the Chart

To install the chart in namespace 'backups'
```console
helm install jellyfin l3st86/jellyfin --namespace backups --set namespace=backups
```

## Uninstalling the Chart

To uninstall the `jellyfin` deployment

```console
helm uninstall jellyfin
```

The command removes all the Kubernetes components associated with the chart **including persistent volumes** and deletes the release.

## Configuration

Read through the [values.yaml](./values.yaml) file. It has several commented out suggested values.
Alternatively, a YAML file that specifies the values for the above parameters can be provided while installing the chart.

```console
helm install jellyfin l3st86/jellyfin -f values.yaml
```

## Changelog

### Version 0.1.1

#### Added

First Version Full working Released
Added new icon

#### Changed

* First Version

### Version 0.1.2

#### Added

Hardware Acceleration in values for GPU

#### Changed

* Changed image from lscr.io to official jellyfin docker image

### Version 0.1.3

#### Added

Fixed Hardware Acceleration in values for GPU Permissions in Security context

#### Changed

* Added fix Hardware Acceleration

