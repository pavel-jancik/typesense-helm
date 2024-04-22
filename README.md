# Typesense Helm chart repo
This is unofficial helm repository with helm chart for typesense.

For helm chart sources see [main](https://github.com/pavel-jancik/typesense-helm/tree/main) branch and [releases](https://github.com/pavel-jancik/typesense-helm/releases).


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
```
