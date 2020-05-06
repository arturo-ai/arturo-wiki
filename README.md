# Wiki.js Helm Chart

The chart requires a live postgresql DB instance.

## Installation

Visit the [wiki-database vault secret](https://vault.arturo.ai/ui/vault/secrets/secret/show/wiki-database) for the following install values.

1. Fill in blank ENV values in ./values.yaml.
2. Install the chart
```shell script
helm install --name wiki . --namespace wiki
```