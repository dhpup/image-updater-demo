# Version: 0.0.3

# Guestbook Example Application

This repository contains the source code to a demo application based on the [Kubernetes guestbook application](https://github.com/kubernetes/examples/tree/master/guestbook-go) for the purposes of demonstrating a GitOps based CI/CD pipeline. 

A code change to this repository will cause:

1. A new [dhpup/guestbook] Docker Hub image to be published with a unique image tag that incorporates the commit SHA into the image tag (e.g. `dhpup/guestbook:sha-e7e75c8`).

## Screenshot

![Guestbook](guestbook-page.png)

