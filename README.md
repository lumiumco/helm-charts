## Usage

[Helm](https://helm.sh) must be installed to use the charts.  Please refer to
Helm's [documentation](https://helm.sh/docs) to get started.

Once Helm has been set up correctly, add the repo as follows:

  helm repo add lumiumco https://lumiumco.github.io/helm-charts

If you had already added this repo earlier, run `helm repo update` to retrieve
the latest versions of the packages.  You can then run `helm search repo
lumiumco` to see the charts.

To install the ratelimit chart:

    helm install ratelimit lumiumco/ratelimit

To uninstall the chart:

    helm uninstall ratelimit
