# Jitsi Meet on Kubernetes (via Helm)

[Jitsi] is a set of Open Source projects that allows you to easily build and deploy secure videoconferencing solutions.

[Jitsi Meet] is a fully encrypted, 100% Open Source videoconferencing solution that you can use all day, every day, for free — with no account needed.

This repository contains the necessary tools to run a Jitsi Meet stack on [Kubernetes] using [Helm].

## Table of contents

* [Quick start](#quick-start)

<hr />

## Quick start

Create a values file based on values.yaml and install the chart using helm.

```
cd k8s
cp values.yaml your-values.yaml
helm install -f your-values.yaml your-installation-nickname .
```
