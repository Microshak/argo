# argo
Argo CD App Config

## Get password
sudo microk8s kubectl -n argocd get secret argocd-initial-admin-secret -o jsonpath="{.data.password}" | base64 -d


 sudo microk8s kubectl apply -f Microshak.yaml


sudo microk8s kubectl port-forward service/argo-cd-argocd-server -n argocd 8080:443
