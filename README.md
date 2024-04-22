# typesense-helm
A typesense helm chart

Inspired by [pcmid/charts/typesense](https://github.com/pcmid/charts/tree/master/charts/typesense) - the best helm chart for typsense I found 
with minor changes taken from [typesense-operator](https://github.com/sai3010/Typesense-Kubernetes-Operator)


# Helm chart repository

For helm chart repository is in the [helm-repo](https://github.com/pavel-jancik/typesense-helm/tree/helm-repo) branch.
You can manually download helm chart from the [releases](https://github.com/pavel-jancik/typesense-helm/releases).


To get the typesense helm chart run:
```sh
helm repo add typesense https://raw.githubusercontent.com/pavel-jancik/typesense-helm/helm-repo/
# "typesense" has been added to your repositories

helm repo update typesense
# Hang tight while we grab the latest from your chart repositories...
# ...Successfully got an update from the "typesense" chart repository
# Update Complete. ⎈Happy Helming!⎈


# List charts in the repo
helm search repo typesense
# NAME                            CHART VERSION   APP VERSION     DESCRIPTION
# typesense/typesense             0.1.2           26.0            Fast, typo tolerant, in-memory fuzzy Search Eng...

# Install the chart with defaults
helm install typesense typesense/typesense
```