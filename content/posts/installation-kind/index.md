---
title: "Getting started on KinD"
date: 2024-10-14T08:00:00+00:00
description: Getting started on KinD
menu:
  sidebar:
    name: Getting started on KinD
    identifier: installation-kind
    weight: 40
params:
  author:
    image: "/images/author/jorge.jpeg"
mermaid: true
---

## Intro

Educates Training Platform is very easy to install locally in order to get started. Just download the `educates` [binary for the latest release](https://github.com/vmware-tanzu-labs/educates-training-platform/releases) for your operating system and architecture, and once placed wherever you put your binaries, just need to run:

```
educates create-cluster
``` 

As easy as that.

Educates Training Platform will be installed on your machine using [KinD (Kubernetes on Docker)](https://kind.sigs.k8s.io/) and will provide, along with the [Educates Training Platform](https://github.com/vmware-tanzu-labs/educates-training-platform) itself, an Ingress Controller ([contour](https://projectcontour.io/)) and policy management ([kyverno](https://kyverno.io/)) to provide a minimal environment for you to start creating or deploying Workshops.

Head to our [Getting started documentation page](https://docs.educates.dev/en/stable/getting-started/quick-start-guide.html) for a more detailed description about the features and options.

## Asciinema

{{< asciinema id="A7X0VSYLdlvf932uMpaXgaJZ4" autoplay="true" loop="true" >}}

