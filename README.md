# h0n9's Helm Charts 📜

## Usage

[Helm](https://helm.sh) must be installed to use the charts. Please refer to
Helm's [documentation](https://helm.sh/docs) to get started.

Once Helm has been set up correctly, add the repo as follows:

```bash
helm repo add h0n9 https://h0n9.github.io/helm-charts
```

If you had already added this repo earlier, run `helm repo update` to retrieve
the latest versions of the packages. You can then run `helm search repo h0n9`
to see the charts.

### Example

To install the `<chart-name>` chart:

```bash
helm upgrade --install <chart-name> h0n9/<chart-name>
```

To uninstall the chart:

```bash
helm delete <chart-name>
```

