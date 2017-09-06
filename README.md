## Code from Kubernetes Webinar Series - Getting Started with Kubernetes
https://www.youtube.com/watch?v=_vHTaIJm9uY


# Configuring Docker and Kubernetes Development Environment
Clone this repo and try each step. For detailed walkthrough refer to the [tutorial](http://thenewstack.io/tutorial-configuring-ultimate-development-environment-kubernetes/) on The New Stack.

## Important K8s commands

Create a Kubernetes deployment with the image:
** kubectl run my-web --image=guillierf/myweb --port=80

Create a Kubernetes service of type NodePort:
** kubectl expose deployment my-web --target-port=80 --type=NodePort
