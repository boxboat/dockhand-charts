# dockhand-secrets-operator
Installs the [dockhand-secrets-operator](https://github.com/boxboat/dockhand-secrets-operator)

## Install Instructions
```
helm repo add dockhand https://dockhand-charts.storage.googleapis.com
helm repo update
helm install --namespace dockhand-secrets-operator dockhand/dockhand-secrets-operator-crd
helm install --namespace dockhand-secrets-operator dockhand/dockhand-secrets-operator
```
