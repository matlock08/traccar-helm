


helm upgrade --install traccar ./traccar --namespace traccar --create-namespace -f ./traccar/values.yaml --kubeconfig ../kubeedge_rpirelay/helm/k8s-master-sfo3-kubeconfig.yaml


helm uninstall --namespace traccar traccar --kubeconfig ../kubeedge_rpirelay/helm/k8s-master-sfo3-kubeconfig.yaml


