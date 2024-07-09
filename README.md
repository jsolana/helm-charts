# helm-charts

Welcome to the Helm Charts Repository! This repository serves as a collection of various Helm charts designed for different proof-of-concept (PoC) scenarios. Please note that these charts are intended for experimental purposes and are not production-ready.

This repository contains Helm charts for various applications and services, each tailored to demonstrate specific use cases or concepts. These charts are useful for:

- Demonstrating new ideas and concepts
- Conducting proof-of-concept (PoC) tests
- Learning and educational purposes

:warning: These Helm charts are not intended for production use.

To use a Helm chart from this repository, follow these steps:

Clone the repository:

```bash
git clone https://github.com/your-username/helm-charts-repo.git
cd helm-charts-repo
```

Install a Helm chart:

```bash
helm install my-release ./chart-directory
Customize the installation using values files if needed:
```

```bash
helm install my-release ./chart-directory -f custom-values.yaml
```

## Usage

[Helm](https://helm.sh) must be installed to use the charts.  Please refer to
Helm's [documentation](https://helm.sh/docs) to get started.

Once Helm has been set up correctly, add the repo as follows:

```sh
  helm repo add jsolana https://jsolana.github.io/helm-charts
```

If you had already added this repo earlier, run `helm repo update` to retrieve
the latest versions of the packages.  You can then run `helm search repo <alias>` to see the charts.

To install the `<chart-name>` chart:

```sh
    helm install my-<chart-name> <alias>/<chart-name>
```

To uninstall the chart:

```sh
    helm delete my-<chart-name>
```
