# [EOL] Node API

The node-api group was migrated to a built-in API in the
[k8s.io/api](https://github.com/kubernetes/api) repo with the
v1.14 release. **This repo is no longer maintained**, and no longer
synced with core kubernetes as of the v1.18 release.

Please use the `RuntimeClass` types located at
[k8s.io/api](https://github.com/kubernetes/api), and the generated
clients located at [k8s.io/client-go](https://github.com/kubernetes/client-go).

## Original Purpose

This repository contains type definitions and client code for the Kubernetes
APIs in the node.k8s.io API group. These APIs are primarily used by the Kubelet
for managing node operations, such as container runtime support.

Consumers of the node APIs can make use of this repository to access
implementations of the APIs.

## Community, discussion, contribution, and support

Learn how to engage with the Kubernetes community on the [community
page](http://kubernetes.io/community/).

You can reach the maintainers of this repository at:

- Slack: #sig-node (on https://kubernetes.slack.com -- get an
  invite at slack.kubernetes.io)
- Mailing List:
  https://groups.google.com/forum/#!forum/kubernetes-sig-node

### Code of Conduct

Participation in the Kubernetes community is governed by the [Kubernetes
Code of Conduct](code-of-conduct.md).

### Contibution Guidelines

See [CONTRIBUTING.md](CONTRIBUTING.md) for more information.
