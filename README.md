---
# acad-k8s-tut
---
notes
---

flux bootstrap github \
  --token-auth \
  --owner=adodabele \
  --repository=acad-k8s-tut \
  --branch=main \
  --path=clusters/staging \
  --personal

kubectl get kustomization -n flux-system
kubectl kustomize --help
kubectl kustomize clusters/staging/flux-system

