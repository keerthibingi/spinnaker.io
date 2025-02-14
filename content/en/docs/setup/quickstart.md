---
title: 'Demo/Evaluation Installations'
linkTitle: 'Quickstart'
weight: 1
description: >
  Quickstart solutions that gives you the ability to try Spinnaker out quickly. These are not meant for production use as is.
aliases:
  - /setup/quickstart/
---

If you want to install Spinnaker on Lightweight Kubernetes (K3s) for proofs of concept, see the open source project [Minnaker](https://github.com/armory/minnaker). You can install Spinnaker in about 10 minutes in a local or cloud VM.

Options for installing Spinnaker in Kubernetes:

- [Spinnaker Helm Chart](https://github.com/OpsMx/spinnaker-helm) is an open source helm chart to install/configure spinnaker in GitOps/Non-GitOps style
- [Spinnaker Operator for Kubernetes](https://github.com/armory/spinnaker-operator) is an open source Kubernetes Operator for deploying and managing Spinnaker. You can install a basic version of Spinnaker or use Kustomize files for advanced configuration.
- [Kubernetes Helm Chart](https://github.com/kubernetes/charts/tree/master/stable/spinnaker) **As of Nov 13, 2020, charts in this repo are no longer updated. **

Guides for installing Spinnaker in specific cloud environments:

> These guides may contain outdated content.

- [Spinnaker for Google Cloud Platform](https://cloud.google.com/docs/ci-cd/spinnaker/spinnaker-for-gcp) 2020
- [Microsoft Azure](https://azure.microsoft.com/en-us/resources/templates/301-jenkins-acr-spinnaker-k8s/) 2018
- [Amazon Web Services](https://aws.amazon.com/about-aws/whats-new/2016/08/netflix-oss-spinnaker-on-the-aws-cloud-quick-start-reference-deployment/) 2016
