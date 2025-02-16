1. Create a new deployment and save it to `deployment.yaml`

`kubectl run simple --image=nginx --dry-run=client -o=yaml > deployment.yaml`