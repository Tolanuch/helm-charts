# This is Tolanuch's helm-charts

## Usage

[Helm](https://helm.sh) must be installed to use the charts.  Please refer to
Helm's [documentation](https://helm.sh/docs) to get started.

Once Helm has been set up correctly, add the repo as follows:

    helm repo add tolanuch-charts https://tolanuch.github.io/helm-charts

If you had already added this repo earlier, run `helm repo update` to retrieve
the latest versions of the packages.  You can then run `helm search repo
tolanuch-charts` to see the charts.

To install the my-own-chart chart:

    helm install my-my-own-chart tolanuch-charts/my-own-chart

To uninstall the chart:

    helm delete my-my-own-chart
