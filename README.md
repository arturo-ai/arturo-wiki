# Wiki.js Helm Chart

The chart requires a live postgresql DB instance.

## Installation

Visit the [wiki-database vault secret](https://vault.arturo.ai/ui/vault/secrets/secret/show/wiki-database) for the following install values.

1. Fill in blank ENV values in `./values.yaml` and DB master password in `./templates/password_secret`.
2. Install the chart
```shell script
helm install --name arturo-wiki . --namespace arturo-wiki
```