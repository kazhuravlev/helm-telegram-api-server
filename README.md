## Usage

[Helm](https://helm.sh) must be installed to use the charts. Please refer to
Helm's [documentation](https://helm.sh/docs) to get started.

Once Helm has been set up correctly, add the repo as follows:

```shell
helm repo add tg-bot-api https://kazhuravlev.github.io/helm-tg-bot-api
```

If you had already added this repo earlier, run `helm repo update` to retrieve
the latest versions of the packages. You can then run `helm search repo
tg-bot-api` to see the charts.

To install the tg-bot-api chart:

```shell
helm install my-tg-bot-api tg-bot-api/tg-bot-api
```

To uninstall the chart:

```shell
helm delete my-tg-bot-api
```
