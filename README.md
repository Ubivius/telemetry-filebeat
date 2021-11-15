# Telemetry-filebeat

Filebeat ships with modules for observability and security data sources that simplify the collection, parsing, and visualization of common log formats down to a single command

## Usage

[Helm](https://helm.sh) must be installed to use the charts.
Please refer to Helm's [documentation](https://helm.sh/docs/) to get started.

- filebeat · elastic/filebeat (https://artifacthub.io/packages/helm/elastic/filebeat)

Once Helm is set up properly, add the repo as follows:

## Get Repo Info

```console
$ helm repo add elastic https://helm.elastic.co
$ helm repo update
```

## Installing the Chart

To install the chart with the release name `filebeat`:

```console
$ helm install filebeat --version <version> elastic/filebeat -f chart/values.yaml
```

## Uninstalling the Chart

To uninstall/delete the filebeat deployment:

```console
$ helm delete filebeat
```

The command removes all the Kubernetes components associated with the chart and deletes the release.
