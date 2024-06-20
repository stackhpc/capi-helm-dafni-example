# capi-helm-dafni-example

See [stackhpc/capi-helm-fluxcd-config](https://github.com/stackhpc/capi-helm-fluxcd-config)
for full usage details.

This repository contains an example configuration for a Kubernetes cluster on STFC Cloud
with all the prerequisites for running the DAFNI platform, in particular:

  * Pod and service CIDRs that do not collide with STFC infrastructure
  * Cilium with the kube-proxy replacement and API gateway enabled
  * Storage classes providing RWO and RWX volumes using Cinder and Manila respectively
  * Monitoring stack enabled
