# Troubleshooting
```shell
helm template [RELEASE_NAME] [CHART] --values [VALUES_FILE]
```
This command processes the chart into Kubernetes manifests and outputs them. It doesn't deploy the chart but simply allows you to see the resulting YAML. Replace `RELEASE_NAME` with a name for your release, `CHART` with the path to your chart directory, and `VALUES_FILE` with the path to your values file. This will show the complete Kubernetes manifests with all template variables populated.