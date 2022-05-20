# Fantastic Peaks GKE infrastructure
A small budget Kubernetes clunter in GKE using TerraForm, [KubeIP](https://github.com/doitintl/kubeip), and Traefik to avoid the fees associated with cloud load balancers.

# Currently running
- [MobileBurd](https://github.com/scottbarnes/mobileburd), a small Flask app that uses Bootstrap to "translate" the main page and trip report content from https://www.snwburd.com/bob into something that renders better on smart phone. [See it in action](https://mobileburd.fishcracker.net/). ./k8s/mobileburd 

Note: gcloud authentication keys go in ./keys
