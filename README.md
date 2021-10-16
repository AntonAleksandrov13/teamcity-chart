## Usage

[Helm](https://helm.sh) must be installed to use the charts.  Please refer to
Helm's [documentation](https://helm.sh/docs) to get started.

Once Helm has been set up correctly, add the repo as follows:

 `helm repo add teamcity-test https://antonaleksandrov13.github.io/teamcity-chart`

If you had already added this repo earlier, run `helm repo update` to retrieve
the latest versions of the packages.  You can then run `helm search repo
teamcity` to see the charts.

To install the teamcity chart:

    helm install my-teamcity teamcity-test/teamcity

To uninstall the chart:

    helm delete my-teamcity