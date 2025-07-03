vinted-tryout-infra-demo
This repository serves as the GitOps source of truth for the vinted-tryout-app.
It contains the Kubernetes manifests (kubernetes/deployment.yaml) that define the desired state of the application's deployment.
Updates to the image tag in deployment.yaml are automatically committed by a GitHub Actions workflow triggered from the application repository (replace with your actual app repo link if desired).
A GitOps agent should monitor this repository to automatically deploy the latest application versions to a Kubernetes cluster.
