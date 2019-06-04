```
kustomize edit add resource exporters/blackbox-exporter/**
kustomize edit add resource exporters/kube-state-metrics/**
kustomize edit add resource exporters/node-exporter/**
kustomize edit add resource prometheus/**
kustomize edit add resource alertmanager/**
kustomize edit add resource grafana/**
```