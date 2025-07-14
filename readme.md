# FinOps Database Handler Notebooks
This [Helm Chart](https://helm.sh/docs/topics/charts/) contains the notebooks for the [finops-database-handler](https://github.com/krateoplatformops/finops-database-handler) required by various Krateo components. Specifically, it uploads all notebooks in the folder [notebook_samples](https://github.com/krateoplatformops/finops-database-handler/tree/0.4.5/notebook_samples) of the [finops-database-handler](https://github.com/krateoplatformops/finops-database-handler).

## How to install

```sh
$ helm repo add krateo https://charts.krateo.io
$ helm repo update krateo
$ helm install finops-notebooks krateo/finops-notebooks
```
