# deskbee/helm

Public Helm chart repository for Deskbee.

## OCI chart

The chart is published to GitHub Container Registry as:

```text
oci://ghcr.io/deskbee/helm/deskbee
```

## Install

```bash
helm install deskbee oci://ghcr.io/deskbee/helm/deskbee --version 1.0.0
```

## Pull

```bash
helm pull oci://ghcr.io/deskbee/helm/deskbee --version 1.0.0
```

## Release process

Any change pushed to `main` under `charts/**` triggers the GitHub Actions workflow that packages and pushes the chart to GHCR.
