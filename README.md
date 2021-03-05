# kube-prometheus kustomize
Kustomize scripts to deploy Prometheus-operator and configurations

## Usage

- Fork this repo
- Edit the `kustomization.yaml` to add your own patches and files.
- Run `./update.sh`
- Keep kube-prometheus configuration, dashboard, alerts up-to-date with `./update.sh`

Example how to add an ingress, alertconfiguration and grafana configuration files:
https://github.com/failfast-ci/kube-prometheus-kustomize
