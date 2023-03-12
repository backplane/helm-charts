# helm-charts

Public [Helm](https://helm.sh) Charts from Backplane.

This repo is managed by the [Helm Chart Releaser Github Action](https://github.com/marketplace/actions/helm-chart-releaser).

## Usage

[Helm](https://helm.sh) must be installed to use the charts.  Please refer to
Helm's [documentation](https://helm.sh/docs) to get started.

Once Helm has been set up correctly, add the repo as follows:

```shell
helm repo add backplane https://backplane.github.io/helm-charts
```

If you had already added this repo earlier, run `helm repo update` to retrieve
the latest versions of the packages.  You can then run `helm search repo
backplane` to see the charts.

To install the `example` chart:

```shell
helm install my-example backplane/example
```

To uninstall the chart:

```shell
helm delete my-example
```