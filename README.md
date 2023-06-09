# helm-charts

Public [Helm](https://helm.sh/) Charts from [Backplane](https://backplane.be/)

The charts are located in the [charts directory](charts/). This GitHub repository utilizes [Helm's chart-releaser-action](https://github.com/helm/chart-releaser-action) to make itself available as a Helm chart repo. The [gh-pages branch](https://github.com/backplane/helm-charts/tree/gh-pages) contains the source files which publish the Helm chart repo.

## Using this Helm Chart Repo

Helm must be installed to use these charts. Please refer to Helm's [documentation](https://helm.sh/docs) to get started. Once Helm has been set up correctly, add the repo as follows:

```shell
helm repo add backplane https://backplane.github.io/helm-charts
```

If you have already added this repo, run `helm repo update` to retrieve the latest versions of the packages.

To search the charts:

```shell
helm search repo backplane
```

To install the `example` chart:

```shell
helm install my-example backplane/example
```

To uninstall the `example` chart:

```shell
helm delete my-example
```
