# dendrite-polylith-k8s

This is an opinionated deployment for dendrite on Kubernetes leveraging Kustomize. Given the current status of dendrite things may change rapidly including the [exclusion of Kafka](https://github.com/matrix-org/dendrite/issues/1847).

This deployment example is can be deployed across multiple clusters leaving it up to the user to generate the private key on their own.

## Getting started

<..>

---
### Credits

- [Flux CI](https://github.com/fluxcd/flux2-kustomize-helm-example)
- [K8s Monolith Deployment](https://github.com/sseneca/k8s-server/tree/master/dendrite)
- [matrix](matrix.org)
- [dendrite](https://github.com/matrix-org/dendrite)
