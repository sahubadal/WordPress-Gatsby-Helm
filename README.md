# WordPress-Gatsby-Helm

## Usage

[Helm](https://helm.sh) must be installed to use the charts.  Please refer to
Helm's [documentation](https://helm.sh/docs) to get started.

Once Helm has been set up correctly, add the repo as follows:
  
    helm repo add wp-gats https://sahubadal.github.io/WordPress-Gatsby-Helm/charts
  
If you had already added this repo earlier, run `helm repo update` to retrieve
the latest versions of the packages.  You can then run `helm search repo wp-gats` to see the charts.

To install the <chart-name> chart:

    helm install <Your-chart-name> wp-gats/wp-gats-helm

To uninstall the chart:

    helm delete <Your-chart-name>
