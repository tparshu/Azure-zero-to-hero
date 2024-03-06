Download CLI 

az login

az_aks get-credentials --name azuredevops --overwrite-existing --resource-group azurecicd

kubectl get pods

kubectl create namespace argocd

kubectl apply -n argocd -f https://raw.githubusercontent.com/argoproj/argo-cd/stable/manifests/install.yaml

kubectl get pods -n argocd

kubectl get secrets -n argocd

kubectl edit secret argocd-initial-admin-secret -n argocd

echo <copy encrypted code> | base64 --decode

kubectl get svc -n argocd

kubectl edit svc argocd-server -n argocd

<local host>: http port 

allow inbound rule from virtual machine skill set
