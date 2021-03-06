# FusionAuth Helm Chart [![Build Status](https://travis-ci.org/FusionAuth/charts.svg?branch=master)](https://travis-ci.org/FusionAuth/charts)

[FusionAuth](https://fusionauth.io/) is a modern platform for Customer Identity and Access Management (CIAM). FusionAuth provides APIs and a responsive web user interface to support login, registration, localized email, multi-factor authentication, reporting and much more.

## Installing the Chart

To install the chart with the release name `my-release`:

```console
$ helm repo add fusionauth https://fusionauth.github.io/charts
$ helm install fusionauth/fusionauth  --name my-release
```

The command deploys FusionAuth and all dependencies (elasticsearch, postgresql) on the Kubernetes cluster with the default configuration. The [configuration](#configuration) section lists the parameters that can be configured during installation.

## Uninstalling the Chart

To uninstall/delete the `my-release` deployment:

```console
$ helm delete my-release
```

The command removes all the Kubernetes components associated with the chart and deletes the release.

## Configuration

See the values.yaml file for configuration options. By default this chart will deploy elasticsearch and postgresql charts to go along with fusionauth.


### Notice
This repository is community maintained and it is provided to assist in your deployment and management of FusionAuth. Use of this software is not covered under the FusionAuth license agreement and is provided "as is" without warranty.  https://fusionauth.io/license
